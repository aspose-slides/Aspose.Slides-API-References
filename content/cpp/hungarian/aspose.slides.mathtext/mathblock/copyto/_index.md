---
title: CopyTo()
second_title: Aspose.Slides for C++ API referencia
description: Másolja a megadott tömbbe.
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/mathblock/copyto/
---
## MathBlock::CopyTo(System::ArrayPtr\<System::SharedPtr\<IMathElement\>\>, int32_t) metódus

Másolja a megadott tömbbe.

```cpp
void Aspose::Slides::MathText::MathBlock::CopyTo(System::ArrayPtr<System::SharedPtr<IMathElement>> array, int32_t arrayIndex) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\> | A tömb, amelybe másolni kell. |
| arrayIndex | **int32_t** | Az index, ahol a másolás kezdődik. |
## Megjegyzések



Példa: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
auto destinationArray = System::MakeArray<System::SharedPtr<IMathElement>>(mathBlock->get_Count());
mathBlock->CopyTo(destinationArray, 0);
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBlock](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)