---
title: SetSuperscript()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea superíndice
type: docs
weight: 79
url: /es/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) método


Crea superíndice

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superíndice (índice superior a la derecha) |

### Valor de retorno

Nuevo elemento matemático del tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Observaciones



Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) método


Crea superíndice

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Superíndice (índice superior a la derecha) |

### Valor de retorno

Nuevo elemento matemático del tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Observaciones



Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathElementBase](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)