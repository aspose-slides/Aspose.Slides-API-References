---
title: MathBlock()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av klassen MathBlock.
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() konstruktor


Initierar en ny instans av klassen [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Anmärkningar


Exempel: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) konstruktor


Skapar ett nytt matematiskt block och lägger det specificerade elementet i det

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Det matematiska elementet som ska placeras i blocket |
## Anmärkningar



Exempel: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) konstruktor


Skapar ett nytt matematiskt block och lägger de specificerade elementen i det

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | De matematiska elementen som ska placeras i blocket |
## Anmärkningar



Exempel: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [MathBlock](../)
* Klass [IMathElement](../../imathelement/)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)