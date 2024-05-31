class Heroi {
    constructor(nome, idade, tipo) {
        this.nome = nome;
        this.idade = idade;
        this.tipo = tipo;
    }

    atacar() {
        let ataque = "";
        switch (this.tipo) {
            case "mago":
                ataque = "usou magia";
                break;
            case "guerreiro":
                ataque = "usou espada";
                break;
            case "monge":
                ataque = "usou artes marciais";
                break;
            case "ninja":
                ataque = "usou shuriken";
                break;
            default:
                ataque = "usou suas habilidades";
        }
        console.log(`O ${this.tipo} atacou usando ${ataque}`);
    }
}

// Criando um objeto do tipo mago
let meuMago = new Heroi("Gandalf", 1000, "mago");
// Chamando o método atacar do mago
meuMago.atacar();

O mago atacou usando Escuridão Abissal.

console.log ("Escuridão Abissal: Esta magia convoca as sombras mais profundas e sinistras, criando uma escuridão densa que pode obscurecer completamente a visão ou até mesmo aprisionar os inimigos em um vórtice de trevas.")

