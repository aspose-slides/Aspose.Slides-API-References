---
title: Delimit()
second_title: Aspose.Slides για C++ API Αναφορά
description: Οριοθετεί τα παιδικά στοιχεία με χαρακτήρα διαχωρισμού (χωρίς τις αγκύλες)
type: docs
weight: 209
url: /el/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) μέθοδος

Δηλώνει τα παιδικά στοιχεία με χαρακτήρα διαχωρισμού (χωρίς τις αγκύλες)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separatorCharacter | char16_t | Χαρακτήρας διαχωρισμού |

### Τιμή Επιστροφής

Το μαθηματικό στοιχείο τύπου [IMathDelimiter](../../imathdelimiter/)

## Παρατηρήσεις

Example: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathDelimiter](../../imathdelimiter/)
* Κλάση [MathBlock](../)
* Ονομαχώρος [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)