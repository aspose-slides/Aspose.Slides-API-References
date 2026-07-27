---
title: CreateMathematicalText()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crear elemento de texto matemático vacío
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() método


Crear un elemento de texto matemático vacío

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```


### Valor devuelto

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) método


Crear un elemento de texto matemático con el valor especificado

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathSymbol | char16_t | símbolo único a usar como valor de texto |

### Valor devuelto

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) método


Crear un elemento de texto matemático vacío con el valor especificado

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |

### Valor devuelto

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) método


Crear un elemento de texto matemático vacío con el valor especificado y propiedades de formato

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | ajustes de formato de texto |

### Valor devuelto

new Mathematical Text

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathematicalText](../../imathematicaltext/)
* Clase [MathematicalTextFactory](../)
* Clase [String](../../../system/string/)
* Clase [IPortionFormat](../../../aspose.slides/iportionformat/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)