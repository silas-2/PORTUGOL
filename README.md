programa
{
    // Calcular maioridade
    funcao inicio()
    {
        // Declaração das variáveis
        inteiro anoNascimento
        inteiro anoAtual = 2024  // Ano atual fixo
        inteiro idade

        // Solicitar o ano de nascimento
        escreva("Digite o ano de nascimento: ")
        leia(anoNascimento)
        
        // Calcular a idade
        idade =  anoAtual - anoNascimento
        
        // Verificar se é maior de idade
        se (idade < 18) 
        
            escreva("Menor de idade\n")
        
       
        senao
            escreva("Maior de idade\n")
        }
    
}
