let alunos = [
    {
        titulo: "Dom Casmurro",
        paginas: 300,
        genero: "clássico",
    },
    {
        titulo: "IT a coisa",
        paginas: 150,
        genero: "terror",
    },
    {
        titulo: "Jason",
        paginas: 70,
        genero: "terror",
    },
    {
        titulo: "Chapéuzinho Vermelho",
        paginas: 10,
        genero: "clássico",
    },
    {
        titulo: "Histórinhas de terror para crianãs",
        paginas: 50,
        genero: "clássico",
    },
]

export function criarPilha(tamanhoPilha = 0.25){
}

export function inserirPilha(livro){
    for(let i = 0; i < livro.length; i++){
        console.log(`${livro[i]} inserido na pilha`)
    }
}

export function retirarPilha(livro){
     for(let i = 0; i< livro.length; i++){
        const LivroRetirado = livro.pop()
     console.log(`${LivroRetirado} retirado da pilha`)
     }
}
export function verificaExistencia(livro){
    for(let i = 0; i< livro.length; i++){
        if(livro[i] === titulo){
            console.log("Achei o livro:"+ titulo)
            return
        }
        console.log("Não achei o livro:" + titulo)
    }
}
