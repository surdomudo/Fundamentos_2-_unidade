# Type Conversion (Conversão de tipo)/ Type coersao (Coerção de tipo)

```js
   var x = Number("0") //Type Conversion, nessa linha é feita uma conversão de tipo explicita

  var y = "2" +3 // Type Coercion, nessa linha é feita uma conversão implícito do valor 3 que é númerico(Number)   para texto(string)

  //Onde usa expressões condicional e repetição, faz necessário um valor boolean (verdadeiro ou falso)
  //Ex
  if(true){
  }

  //Caso não fior informado uma expressão ou um valor boolean diretamente, ele fará um Type coercion (Coersão de tipo)
  //Ex.
  if(0) { //Nessa linha ira fazer uma conversão do 0 para um boolean (verdadeiro ou falso), nesse caso 0 será falso
  } 
```
