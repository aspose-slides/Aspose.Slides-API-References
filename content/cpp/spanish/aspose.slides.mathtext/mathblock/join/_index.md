---
title: Join()
second_title: Referencia de API de Aspose.Slides para C++
description: Une un elemento matemático con este bloque matemático
type: docs
weight: 183
url: /es/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) método

Une un elemento matemático con este bloque matemático

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El elemento a unir |

### Valor devuelto

La instancia actual de [IMathBlock](../../imathblock/)
## Observaciones



Ejemplo:
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) método

Une un texto matemático con este bloque matemático

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Texto matemático a unir |

### Valor devuelto

Un nuevo [IMathBlock](../../imathblock/) que contiene esta instancia y el argumento especificado
## Observaciones



Ejemplo:
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathBlock](../../imathblock/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathBlock](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)