---
title: MathBlock()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase MathBlock.
type: docs
weight: 66
url: /es/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() constructor


Inicializa una nueva instancia de la clase [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Comentarios


Ejemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) constructor


Crea un nuevo bloque matemático y coloca el elemento especificado en él

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El elemento matemático que se coloca en el bloque |
## Comentarios



Ejemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) constructor


Crea un nuevo bloque matemático y coloca los elementos especificados en él

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Elementos matemáticos que se colocan en el bloque |
## Comentarios



Ejemplo: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MathBlock](../)
* Class [IMathElement](../../imathelement/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)