---
title: CreateMathBlock()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crear un bloque matemático
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() método

Crear un bloque matemático

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```

### Valor devuelto

nuevo bloque matemático

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) método

Crear un bloque matemático y colocar el elemento en él

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Un elemento matemático |

### Valor devuelto

nuevo bloque matemático

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) método

Crear un bloque matemático y colocar los elementos en él

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | elementos matemáticos |

### Valor devuelto

nuevo bloque matemático

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathBlock](../../imathblock/)
* Clase [IMathBlockFactory](../)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathElementCollection](../../imathelementcollection/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)