#Tags de entradas
## <input>
- Um dos mais usados em formulários
- Aceita os mais diversos tipos de dados
- Um dos mais poderosos e complexo
- Elevado número de combinações

### Atributos

- type
- name
- id
- autocomplete
- autofocus
- disabled
- value
- readonly
- form 
- required
- placehoder


## input PASSAWORD

<input type="password"/>

- Colocar uma senha de maneira segura 
- Esconde o que está sendo digitado no campo
- O estilo da apresentação do campo, depende do User Agent

### Atributos

- minlength / maxlength
- size
- pattern 
- placeholder
- readonly / disabled
- required
- inputmode
- autocomplete

## input e-mail

<input type="email" />

- espera que o usuário digite um email
- ira validar se o valor digitado é um email

### atributos
- placeholder
- readonly / disabled
- value
- required
- mutiple 
- minlength / maxlength
- size
- pattern
- list 

## input URL

<input type="url"/>

- Espera que o usuário digite uma url
- Irá validar se o valor digitado é uma url

### atributos 
- placeholder
- readonly / disabled
- value
- required
- minlength / maxlength
- size
- pattern
- list
- spellcheck true ou false

## input file

<input type="file"/>

- Usuário poderá escolher 1 ou mais arquivos para enviar no formulário

### Atributos 

- value
- accept 
- files
- multiple

envio dos arquivos 
Para envio envios dos arquivos o formulário deverá utilizar o método POST e o atributo enctype como "multipart/form-data"

## input color
<input type="color" />

- interface para selecionar cor
- color picker

### Atributos 
- value: RGB
- list

## input checkbox

<input type="checkbox">

- caixas que podem ser marcadas
- selecionar um valor para ser enviado
- se não selecionado, não será enviado nenhum dado

### Atributos
- globais 
- values
- checked

MARCAR multiplos valores 
- usaremos o atributo 'name' como o mesmo nome para diversos campos

## input hidden
<input type="hidden" id="timestamp" name="timestamp" value="1286705410">

- Invisível ao usuário
- Será enviado com o formulário
- Não recebera foco
- Leitores de tela não percebem esse campo

## input radio
<input type="radio">

- Projeto para selecionar uma única opção de um grupo de opções

### Atributos essenciais
- checked
- value

## Textarea
<textarea></textarea>
- mais de uma linha
- útil para textos grandes

### Atributos 
- id
- name
- rows e cols
- maxiength e minlength
- wrap
- outros comuns aos <input>s
    - autocomplete, autofocus, disabled, placeholder, readonly, form, required

## select

<select>

- controle que fornece um menu de opções

## option
<option>

- contem as opções a serem selecionadas
- atributos necessários 
	value

### Atributos unicos
- mutiple
- size

## OPTGROUP


## SEARCH

<input type="search" />

- para campos de busca
- é igual ao campo de tipo 'text' mas poderá ser um pouco diferente dependendo do user agent

### atributos 
- list / <datalist>
- pattern
- aria-label 

## input number

<input type="number" />

- Entrada de números

### Atributos
- min/max
- step
- valeu
- placeholder
- disable
- list

## input range
<input type="range" />

- controle para selecionar um valor numérico
- slider ou dial control

### Atributos
- min/max
- step

sem precisão numérica, porém é possível colocar um valor mínimo e máximo
_____________________________________
### outros campos interessantes
(mas que não tem uma ótimo suporte)
caniuse.com

<input type="date">
<input type="datetime-local">
<input type="month">
<input type="time">
<input type="week">
