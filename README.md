
---

## 🧠 Conceitos Aplicados

### ✔️ Encapsulamento
Os atributos das classes são privados e acessados apenas por métodos públicos (`getters` e `setters`).

### ✔️ Herança
Classes como `Filme` e `Serie` compartilham comportamentos comuns e especializam seus próprios cálculos, como duração.

### ✔️ Polimorfismo
A classe `CalculadoraDeTempo` trabalha com diferentes tipos de conteúdo (filmes e séries) sem conhecer suas implementações específicas.

### ✔️ Interface
A interface `Classificavel` permite que diferentes classes sejam avaliadas e recomendadas pelo `FiltroRecomendacao`.

---

## ⚙️ Funcionalidades Implementadas

- Exibição de ficha técnica de filmes e séries
- Avaliação de conteúdos
- Cálculo automático de média de avaliações
- Contabilização de reproduções e curtidas
- Cálculo do tempo total para maratonar conteúdos
- Recomendação baseada em nota ou visualizações

---

## ▶️ Execução

A aplicação é executada pela classe:

```java
br.com.alura.screenmatch.principal.Principal
