---
title: Size
second_title: Referência da API Java do Aspose.Slides para Android
description: Classe para descrever dimensões de largura e altura em alguma unidade arbitrária.
type: docs
url: /pt/com.aspose.slides.android/size/
---
**Herança:**
java.lang.Object
```
public class Size
```

Classe para descrever dimensões de largura e altura em alguma unidade arbitrária.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Cria uma nova instância de Size. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getWidth()](#getWidth--) | Obtém a largura do tamanho. |
| [getHeight()](#getHeight--) | Obtém a altura do tamanho. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se este tamanho é igual a outro tamanho. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Retorna o tamanho representado como uma string no formato "WxH" |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Cria uma nova instância de Size.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | int | A largura do tamanho |
| height | int | A altura do tamanho |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtém a largura do tamanho.

**Retorna:**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtém a altura do tamanho.

**Retorna:**
int - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se este tamanho é igual a outro tamanho.

Dois tamanhos são iguais se e somente se ambas as larguras e alturas forem iguais.

Um objeto Size nunca é igual a nenhum outro tipo de objeto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Retorna:**
boolean -  true  se os objetos eram iguais,  false  caso contrário
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Retorna:**
int
### toString() {#toString--}
```
public String toString()
```


Retorna o tamanho representado como uma string no formato "WxH"

**Retorna:**
java.lang.String - representação em string do tamanho