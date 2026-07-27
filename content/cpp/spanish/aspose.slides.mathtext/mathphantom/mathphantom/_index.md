---
title: MathPhantom()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase MathPhantom usando el elemento matemático base especificado.
type: docs
weight: 144
url: /es/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) constructor

Inicializa una nueva instancia de la clase [MathPhantom](../) usando el elemento matemático base especificado.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El [IMathElement](../../imathelement/) base cuya visibilidad y disposición será controlada por el fantasma. Este elemento define el contenido que puede ser ocultado o mostrado, mientras sigue afectando la alineación geométrica de la matemática circundante. |

## Observaciones

El elemento fantasma se usa para reservar o suprimir el espacio visual de su expresión base sin necesariamente mostrarlo. Corresponde al elemento OMML **<m:phant>**.

Ejemplo:
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathPhantom](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)