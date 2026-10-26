---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides για την αναφορά API C++
description: Δημιουργεί υπογείωση και ανωγείωση στα δεξιά
type: docs
weight: 92
url: /el/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) μέθοδος


Δημιουργεί υπογείωση και ανωγείωση στα δεξιά

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Υπογείωση (κατώτερος δείκτης στα δεξιά) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ανωγείωση (ανώτερος δείκτης στα δεξιά) |

### Τιμή επιστροφής

Νέο μαθηματικό στοιχείο τύπου [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) μέθοδος


Δημιουργεί υπογείωση και ανωγείωση στα δεξιά

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Υπογείωση (κατώτερος δείκτης στα δεξιά) |
| superscript | [System::String](../../../system/string/) | Ανωγείωση (ανώτερος δείκτης στα δεξιά) |

### Τιμή επιστροφής

Νέο μαθηματικό στοιχείο τύπου [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathElementBase](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)