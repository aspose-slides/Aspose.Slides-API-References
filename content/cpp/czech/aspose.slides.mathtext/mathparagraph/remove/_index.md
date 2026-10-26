---
title: Remove()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraní první výskyt konkrétního objektu ze sbírky/>.
type: docs
weight: 105
url: /cs/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) metoda


Odstraní první výskyt konkrétního objektu ze sbírky/>. 

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Objekt, který má být odstraněn ze sbírky. |

### Návratová hodnota

true, pokud byl *mathBlock* úspěšně odstraněn ze sbírky; jinak false. Tato metoda také vrací false, pokud *mathBlock* nebyl nalezen v původní sbírce/>.

## Poznámky



Příklad: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBlock](../../imathblock/)
* Třída [MathParagraph](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)