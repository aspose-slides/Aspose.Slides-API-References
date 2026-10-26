---
title: IMathFunction
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica uma função de um argumento.
type: docs
url: /pt/com.aspose.slides/imathfunction/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Especifica uma função de um argumento.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [getName()](#getName--) | Nome da função Por exemplo, nomes de funções são sin e cos |
| [getBase()](#getBase--) | Argumento da Função |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


Nome da função Por exemplo, nomes de funções são sin e cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumento da Função

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)