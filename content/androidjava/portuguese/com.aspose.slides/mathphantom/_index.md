---
title: MathPhantom
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto matemático fantasma ltmphantgt que afeta o layout de seu elemento filho sem necessariamente exibi-lo.
type: docs
url: /pt/com.aspose.slides/mathphantom/
---
**Herança:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Representa um objeto matemático fantasma (<m:phant>) que afeta o layout de seu elemento filho sem necessariamente exibi-lo. Um fantasma pode ocultar sua expressão base enquanto preserva sua largura, altura ou profundidade para alinhar fórmulas ou reservar espaço. A visibilidade e o comportamento geométrico são controlados por propriedades como Show, ZeroWid, ZeroAsc, ZeroDesc e Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Ocultar o conteúdo
>  phantom.setZeroWidth(false);     // Manter a largura
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Inicializa uma nova instância da classe [MathPhantom](../../com.aspose.slides/mathphantom) usando o elemento matemático base especificado. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getShow()](#getShow--) | Obtém ou define um valor que indica se o elemento base é exibido. |
| [setShow(boolean value)](#setShow-boolean-) | Obtém ou define um valor que indica se o elemento base é exibido. |
| [getZeroWidth()](#getZeroWidth--) | Obtém ou define um valor que indica se a largura do elemento base deve ser tratada como zero. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Obtém ou define um valor que indica se a largura do elemento base deve ser tratada como zero. |
| [getZeroAsc()](#getZeroAsc--) | Obtém ou define um valor que indica se a ascensão (altura acima da linha de base) do elemento base deve ser tratada como zero. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Obtém ou define um valor que indica se a ascensão (altura acima da linha de base) do elemento base deve ser tratada como zero. |
| [getZeroDesc()](#getZeroDesc--) | Obtém ou define um valor que indica se a descida (profundidade abaixo da linha de base) do elemento base deve ser tratada como zero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Obtém ou define um valor que indica se a descida (profundidade abaixo da linha de base) do elemento base deve ser tratada como zero. |
| [getTransp()](#getTransp--) | Obtém ou define um valor que indica se o fantasma é transparente para regras de espaçamento baseadas em classe. |
| [setTransp(boolean value)](#setTransp-boolean-) | Obtém ou define um valor que indica se o fantasma é transparente para regras de espaçamento baseadas em classe. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriedades de Caracter de Controle |
| [getChildren()](#getChildren--) | Obter elementos filhos |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```


Inicializa uma nova instância da classe [MathPhantom](../../com.aspose.slides/mathphantom) usando o elemento matemático base especificado.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | O [IMathElement](../../com.aspose.slides/imathelement) base cuja visibilidade e layout serão controlados pelo fantasma. Este elemento define o conteúdo que pode ser ocultado ou exibido, enquanto ainda afeta o alinhamento geométrico da matemática circundante. |

O elemento fantasma é usado para reservar ou suprimir o espaço visual de sua expressão base sem necessariamente exibí-lo. Corresponde ao elemento OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argumento base

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```


Obtém ou define um valor que indica se o elemento base é exibido.

--------------------

Quando false, o elemento base é ocultado mas ainda pode ocupar espaço dependendo de outras configurações do fantasma. Corresponde ao atributo OMML m:show.

**Retorna:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```


Obtém ou define um valor que indica se o elemento base é exibido.

--------------------

Quando false, o elemento base é ocultado mas ainda pode ocupar espaço dependendo de outras configurações do fantasma. Corresponde ao atributo OMML m:show.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```


Obtém ou define um valor que indica se a largura do elemento base deve ser tratada como zero.

--------------------

Quando true, o fantasma não reserva espaço horizontal para sua base. Corresponde ao atributo OMML m:zeroWid.

**Retorna:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```


Obtém ou define um valor que indica se a largura do elemento base deve ser tratada como zero.

--------------------

Quando true, o fantasma não reserva espaço horizontal para sua base. Corresponde ao atributo OMML m:zeroWid.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```


Obtém ou define um valor que indica se a ascensão (altura acima da linha de base) do elemento base deve ser tratada como zero.

--------------------

Quando true, o fantasma não eleva a linha de base da linha matemática circundante. Corresponde ao atributo OMML m:zeroAsc.

**Retorna:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```


Obtém ou define um valor que indica se a ascensão (altura acima da linha de base) do elemento base deve ser tratada como zero.

--------------------

Quando true, o fantasma não eleva a linha de base da linha matemática circundante. Corresponde ao atributo OMML m:zeroAsc.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```


Obtém ou define um valor que indica se a descida (profundidade abaixo da linha de base) do elemento base deve ser tratada como zero.

--------------------

Quando true, o fantasma não abaixa a linha de base da linha matemática circundante. Corresponde ao atributo OMML m:zeroDesc.

**Retorna:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```


Obtém ou define um valor que indica se a descida (profundidade abaixo da linha de base) do elemento base deve ser tratada como zero.

--------------------

Quando true, o fantasma não abaixa a linha de base da linha matemática circundante. Corresponde ao atributo OMML m:zeroDesc.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```


Obtém ou define um valor que indica se o fantasma é transparente para regras de espaçamento baseadas em classe.

--------------------

Quando true, operadores e símbolos dentro do fantasma ainda afetam o espaçamento matemático ao redor do fantasma (como se fossem visíveis). Quando false, o espaçamento baseado em classe é ignorado. Corresponde ao atributo OMML m:transp.

**Retorna:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```


Obtém ou define um valor que indica se o fantasma é transparente para regras de espaçamento baseadas em classe.

--------------------

Quando true, operadores e símbolos dentro do fantasma ainda afetam o espaçamento matemático ao redor do fantasma (como se fossem visíveis). Quando false, o espaçamento baseado em classe é ignorado. Corresponde ao atributo OMML m:transp.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propriedades de Caracter de Controle

**Retorna:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obter elementos filhos

**Retorna:**
com.aspose.slides.IMathElement[]