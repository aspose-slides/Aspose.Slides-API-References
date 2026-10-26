---
title: Clear()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort alla element från samlingen.
type: docs
weight: 118
url: /sv/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() metod


Tar bort alla element från samlingen.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Anmärkningar


Exempel: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Se även

* Klass [IMathBlockCollection](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)