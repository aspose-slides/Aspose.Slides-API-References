---
title: SizeF
second_title: Aspose.Slides para Android via Referência da API Java
description: Classe para descrever dimensões de largura e altura em alguma unidade arbitrária com valores de ponto flutuante.
type: docs
url: /pt/com.aspose.slides.android/sizef/
---
**Herança:**
java.lang.Object
```
public class SizeF
```

Classe para descrever dimensões de largura e altura em alguma unidade arbitrária com valores de ponto flutuante.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Cria uma nova instância de SizeF. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getWidth()](#getWidth--) | Obtém a largura do tamanho. |
| [getHeight()](#getHeight--) | Obtém a altura do tamanho. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se este tamanho é igual a outro tamanho. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Retorna o tamanho representado como uma string no formato  "WxH"  |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Cria uma nova instância de SizeF.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | float | A largura do tamanho |
| height | float | A altura do tamanho |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtém a largura do tamanho.

**Retorna:**
float - width
### getHeight() {#getHeight--}
```
public float getHeight()
```


Obtém a altura do tamanho.

**Retorna:**
float - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se este tamanho é igual a outro tamanho.

Dois tamanhos são iguais se, e somente se, ambas as suas larguras e alturas forem iguais.

Para esse fim, os valores float de largura/altura são considerados iguais se, e somente se, o método Float\#floatToIntBits(float).floatToIntBits(float) retornar o mesmo valor  int  quando aplicado a cada um.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Retorna:**
boolean -  true  se os objetos forem iguais,  false  caso contrário
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


Retorna o tamanho representado como uma string no formato  "WxH" 

**Retorna:**
java.lang.String - representação em string do tamanho