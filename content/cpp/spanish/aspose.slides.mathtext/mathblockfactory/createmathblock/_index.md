---
title: CreateMathBlock()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crear un bloque matemático
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() method


Crear un bloque matemático

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```


### Valor devuelto

nuevo bloque matemático

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) method


Crear un bloque matemático y colocar el elemento en él

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Un elemento matemático |

### Valor devuelto

nuevo bloque matemático

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) method


Crear un bloque matemático y colocar los elementos en él

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | elementos matemáticos |

### Valor devuelto

nuevo bloque matemático

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathBlock](../../imathblock/)
* Clase [MathBlockFactory](../)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathElementCollection](../../imathelementcollection/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)