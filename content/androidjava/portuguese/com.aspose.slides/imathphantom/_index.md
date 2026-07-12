---
title: IMathPhantom
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto matemático fantasma ltmphantgt que afeta o layout do seu elemento filho sem necessariamente exibi-lo.
type: docs
url: /pt/com.aspose.slides/imathphantom/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Representa um objeto matemático fantasma (<m:phant>) que afeta o layout de seu elemento filho sem necessariamente exibí-lo. Um fantasma pode ocultar sua expressão base ao mesmo tempo que preserva sua largura, altura ou profundidade para alinhar fórmulas ou reservar espaço. A visibilidade e o comportamento geométrico são controlados por propriedades como Show, ZeroWid, ZeroAsc, ZeroDesc e Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Ocultar o conteúdo
>  phantom.setZeroWidth(false);     // Manter a largura
>  ```

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
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumento base

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```


**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

Obtém ou define um valor que indica se o elemento base é exibido.

--------------------

Quando false, o elemento base fica oculto mas ainda pode ocupar espaço dependendo de outras configurações do fantasma. Corresponde ao atributo OMML m:show.

**Retorna:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Obtém ou define um valor que indica se o elemento base é exibido.

--------------------

Quando false, o elemento base fica oculto mas ainda pode ocupar espaço dependendo de outras configurações do fantasma. Corresponde ao atributo OMML m:show.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Obtém ou define um valor que indica se a largura do elemento base deve ser tratada como zero.

--------------------

Quando true, o fantasma não reserva espaço horizontal para sua base. Corresponde ao atributo OMML m:zeroWid.

**Retorna:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
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
public abstract boolean getZeroAsc()
```

Obtém ou define um valor que indica se a ascensão (altura acima da linha de base) do elemento base deve ser tratada como zero.

--------------------

Quando true, o fantasma não eleva a linha de base da linha matemática circundante. Corresponde ao atributo OMML m:zeroAsc.

**Retorna:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
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
public abstract boolean getZeroDesc()
```

Obtém ou define um valor que indica se a descida (profundidade abaixo da linha de base) do elemento base deve ser tratada como zero.

--------------------

Quando true, o fantasma não abaixa a linha de base da linha matemática circundante. Corresponde ao atributo OMML m:zeroDesc.

**Retorna:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
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
public abstract boolean getTransp()
```

Obtém ou define um valor que indica se o fantasma é transparente para regras de espaçamento baseadas em classe.

--------------------

Quando true, operadores e símbolos dentro do fantasma ainda afetam o espaçamento matemático ao redor do fantasma (como se fosse visível). Quando false, o espaçamento baseado em classe é ignorado. Corresponde ao atributo OMML m:transp.

**Retorna:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Obtém ou define um valor que indica se o fantasma é transparente para regras de espaçamento baseadas em classe.

--------------------

Quando true, operadores e símbolos dentro do fantasma ainda afetam o espaçamento matemático ao redor do fantasma (como se fosse visível). Quando false, o espaçamento baseado em classe é ignorado. Corresponde ao atributo OMML m:transp.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |