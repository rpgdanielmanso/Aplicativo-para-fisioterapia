

# calculadora de rendimentos por atendimento de fisioterapia

// const val i = valor do pacote de 10 atendimentos
// const val s = número de sócios a dividir os rendimentos
const val i = 900
const val s = 2
fun main(){
    

    var sessoes = (1 .. 10).random()
    var pacientes = (1 .. 12).random()
    var aReceber = ((sessoes * (i/10)/s)*pacientes)
    println("Atendimentos "+sessoes)
    println("Pacientes "+pacientes)
    println("Total a receber " + i*pacientes)
    println("Cada sócio irá receber R$"+ aReceber)


}