---
title: Insert()
second_title: Aspose.Slides for C++ API Referencia
description: Beszúrja az IMathBlock-ot a gyűjteménybe a megadott indexnél.
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) metódus

Beszúrja a(z) [IMathBlock](../../imathblock/) a gyűjteménybe a megadott indexnél.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | A nullával kezdődő index, amelynél a tételt be kell illeszteni. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | A beszúrandó [IMathBlock](../../imathblock/). |
## Megjegyzések

Példa:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## Kapcsolódó

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [IMathBlockCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)