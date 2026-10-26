---
title: SlideSize
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o tamanho e a orientação de um slide.
type: docs
url: /pt/com.aspose.slides/slidesize/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Representa o tamanho e a orientação de um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getSize()](#getSize--) | Obtém as dimensões do slide em pontos. |
| [getType()](#getType--) | Obtém o tipo de tamanho do slide. |
| [getOrientation()](#getOrientation--) | Obtém ou define a orientação do slide. |
| [setOrientation(int value)](#setOrientation-int-) | Obtém ou define a orientação do slide. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Define o tamanho do slide por tipo e escala o conteúdo existente. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Define as dimensões do slide explicitamente e escala o conteúdo existente. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```

Obtém as dimensões do slide em pontos.

--------------------

Atribuir um novo valor redefinie a propriedade \#getType.getType para [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) e define \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Retorna:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```

Obtém o tipo de tamanho do slide.

--------------------

Atribuir qualquer valor diferente de [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajusta o \#getSize.getSize de acordo com as dimensões predefinidas, mantendo a \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) atual.

**Retorna:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

Obtém ou define a orientação do slide.

--------------------

Alterar este valor troca a largura e a altura do slide.

**Retorna:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
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
public final void setSize(int type, int scaleType)
```

Define o tamanho do slide por tipo e escala o conteúdo existente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | O tamanho de slide predefinido a ser aplicado. |
| scaleType | int | O modo de dimensionamento de conteúdo a ser usado.

--------------------

Atribuir qualquer valor diferente de [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajusta o \#getSize.getSize com base no tipo selecionado, preservando \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |
### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

Define as dimensões do slide explicitamente e escala o conteúdo existente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | float | A nova largura do slide, em pontos. |
| height | float | A nova altura do slide, em pontos. |
| scaleType | int | O modo de dimensionamento de conteúdo a ser usado.

--------------------

Isso redefine a propriedade \#getType.getType para [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) e define \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |