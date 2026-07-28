---
title: CopyTo()
second_title: Aspose.Slides C++ API Hivatkozás
description: Átmásolja a megadott tömbbe.
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/imathelementcollection/copyto/
---
## IMathElementCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IMathElement\>\>, int32_t) metódus

Átmásolja a megadott tömbbe.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IMathElement>> array, int32_t arrayIndex)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\> | A másolandó tömb. |
| arrayIndex | **int32_t** | Az index, ahol a másolás kezdődik. |
## Megjegyzés



Példa: 
```cpp
System::SharedPtr<IMathElementCollection> collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
auto destinationArray = System::MakeArray<System::SharedPtr<IMathElement>>(collection->get_Count());
collection->CopyTo(destinationArray, 0);
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathElementCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)