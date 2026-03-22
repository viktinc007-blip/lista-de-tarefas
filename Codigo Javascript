Codigo JS

## JS
function adicionar() {
  let input = document.getElementById("tarefa");
  let texto = input.value;

  if (texto === "") return; // não adiciona vazio

  let lista = document.getElementById("lista");

  let item = document.createElement("li");
  item.textContent = texto;

  // cria botão excluir
  let botao = document.createElement("button");
  botao.textContent = "Excluir";

  // função para remover tarefa
  botao.onclick = function() {
    item.remove();
  };

  item.appendChild(botao);
  lista.appendChild(item);

  input.value = ""; // limpa o campo
}
