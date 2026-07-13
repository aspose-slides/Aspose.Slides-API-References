---
title: MathLimitFactory
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Umożliwia tworzenie IMathLimit
type: docs
url: /pl/com.aspose.slides/mathlimitfactory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Umożliwia tworzenie IMathLimit

--------------------

Dla zgodności z COM
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Tworzy IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy IMathLimit z limitem na dole |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Tworzy IMathLimit

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy, do którego zastosować limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Element limitu |
| upperLimit | boolean | Ustawia położenie limitu na górze |

**Zwraca:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nowy limit matematyczny
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Tworzy IMathLimit z limitem na dole

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy, do którego zastosować limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Element limitu |

**Zwraca:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nowy limit matematyczny