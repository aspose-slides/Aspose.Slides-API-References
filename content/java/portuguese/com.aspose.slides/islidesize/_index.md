---
title: ISlideSize
second_title: Referência da API Aspose.Slides para Java
description: Representa o tamanho e a orientação de um slide.
type: docs
url: /pt/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Representa o tamanho e a orientação de um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getSize()](#getSize--) | Gets the slide dimensions in points. |
| [getType()](#getType--) | Gets the slide size type. |
| [getOrientation()](#getOrientation--) | Gets or sets the slide orientation. |
| [setOrientation(int value)](#setOrientation-int-) | Gets or sets the slide orientation. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Sets the slide size by type and scales existing content. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Sets the slide dimensions explicitly and scales existing content. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Obtém as dimensões do slide em pontos.

--------------------

Atribuir um novo valor redefine a propriedade \#getType.getType para [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) e define \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Retorna:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```


Obtém o tipo de tamanho do slide.

--------------------

Atribuir qualquer valor diferente de [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajusta o \#getSize.getSize de acordo com as dimensões predefinidas, mantendo a atual \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Retorna:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Obtém ou define a orientação do slide.

--------------------

Alterar este valor troca a largura e a altura do slide.

**Retorna:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


Obtém ou define a orientação do slide.

--------------------

Alterar este valor troca a largura e a altura do slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


Define o tamanho do slide por tipo e escala o conteúdo existente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | O tamanho de slide predefinido a ser aplicado. |
| scaleType | int | O modo de escala de conteúdo a ser usado. |

--------------------

Atribuir qualquer valor diferente de [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajusta o \#getSize.getSize com base no tipo selecionado, preservando \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


Define explicitamente as dimensões do slide e escala o conteúdo existente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | float | A nova largura do slide, em pontos. |
| height | float | A nova altura do slide, em pontos. |
| scaleType | int | O modo de escala de conteúdo a ser usado. |

--------------------

Isso redefine a propriedade \#getType.getType para [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) e define o \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |