---
title: Remove()
second_title: Aspose.Slides için C++ API Referansı
description: Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır/>.
type: docs
weight: 105
url: /tr/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) yöntemi


Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır/> .

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Koleksiyondan kaldırılacak nesne. |

### Dönüş Değeri

true, eğer *mathBlock* koleksiyondan başarıyla kaldırıldıysa; aksi takdirde false. Bu yöntem ayrıca *mathBlock* orijinal koleksiyonda bulunamazsa false döndürür/> .

## Açıklamalar



Örnek: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)