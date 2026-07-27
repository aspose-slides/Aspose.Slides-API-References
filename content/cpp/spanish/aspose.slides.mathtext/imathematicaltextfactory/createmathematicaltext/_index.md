---
title: CreateMathematicalText()
second_title: Referencia de API de Aspose.Slides para C++
description: Crear elemento de texto matemático vacío
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() método

Crea un elemento de texto matemático vacío

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### Valor devuelto

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) método

Crea un elemento de texto matemático con el valor especificado

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathSymbol | char16_t | símbolo único para usar como valor de texto |

### Valor devuelto

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) método

Crea un elemento de texto matemático vacío con el valor especificado

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |

### Valor devuelto

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) método

Crea un elemento de texto matemático vacío con el valor especificado y propiedades de formato

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | configuración de formato de texto |

### Valor devuelto

new Mathematical Text

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathematicalText](../../imathematicaltext/)
* Clase [IMathematicalTextFactory](../)
* Clase [String](../../../system/string/)
* Clase [IPortionFormat](../../../aspose.slides/iportionformat/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)