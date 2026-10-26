---
title: Delimit()
second_title: Referencia de API de Aspose.Slides para C++
description: Delimita los argumentos usando el carácter delimitador especificado
type: docs
weight: 144
url: /es/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) método


Delimita los argumentos usando el carácter delimitador especificado

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorCharacter | char16_t | delimiter character |

### Valor devuelto

Este objeto después de aplicar el carácter delimitador
## Observaciones



Ejemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)