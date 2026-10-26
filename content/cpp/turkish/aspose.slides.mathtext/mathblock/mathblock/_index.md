---
title: MathBlock()
second_title: Aspose.Slides for C++ API Referansı
description: MathBlock sınıfının yeni bir örneğini başlatır.
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() yapıcı


[MathBlock](../) sınıfının yeni bir örneğini başlatır.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Açıklamalar


Örnek: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) yapıcı


Yeni bir matematiksel blok oluşturur ve belirtilen öğeyi içine yerleştirir

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Bloğa konulacak matematiksel öğe |
## Açıklamalar



Örnek: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) yapıcı


Yeni bir matematiksel blok oluşturur ve belirtilen öğeleri içine yerleştirir

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Bloğa konulacak matematiksel öğeler |
## Açıklamalar



Örnek: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MathBlock](../)
* Class [IMathElement](../../imathelement/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)