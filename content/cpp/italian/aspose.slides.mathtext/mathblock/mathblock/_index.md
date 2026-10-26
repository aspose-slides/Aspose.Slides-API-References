---
title: MathBlock()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe MathBlock.
type: docs
weight: 66
url: /it/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() costruttore

Inizializza una nuova istanza della classe [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Osservazioni

Esempio: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) costruttore

Crea un nuovo blocco matematico e inserisce l'elemento specificato al suo interno

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'elemento matematico da inserire nel blocco |
## Osservazioni



Esempio: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) costruttore

Crea un nuovo blocco matematico e inserisce gli elementi specificati al suo interno

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Elementi matematici da inserire nel blocco |
## Osservazioni



Esempio: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MathBlock](../)
* Class [IMathElement](../../imathelement/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)