---
title: SetSuperscript()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea superíndice
type: docs
weight: 92
url: /es/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) método

Crea superíndice

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superíndice (índice superior a la derecha) |

### Valor devuelto

Nuevo elemento matemático de tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)

## Observaciones



Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) método

Crea superíndice

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Superíndice (índice superior a la derecha) |

### Valor devuelto

Nuevo elemento matemático de tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)

## Observaciones



Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Clase [IMathElement](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)