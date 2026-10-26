---
title: Delimit()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει τα όρια όλων των θυγατρικών στοιχείων με χαρακτήρα διαχωριστή (χωρίς τις αγκύλες)
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) μέθοδος


Καθορίζει τα όρια όλων των θυγατρικών στοιχείων με χαρακτήρα διαχωριστή (χωρίς τις αγκύλες)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | Χαρακτήρας που χρησιμοποιείται ως διαχωριστής |

### Return Value

Παράδειγμα του στοιχείου [IMathDelimiter](../../imathdelimiter/) element
## Remarks



Παράδειγμα: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathDelimiter](../../imathdelimiter/)
* Κλάση [IMathBlock](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)