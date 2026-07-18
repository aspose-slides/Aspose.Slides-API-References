---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί υπο- και ανωδείκτη στα δεξιά
type: docs
weight: 105
url: /el/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) μέθοδος

Δημιουργεί υπο- και ανωδείκτη στα δεξιά

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscript (lower index on the right) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superscript (upper index on the right) |

### Τιμή Επιστροφής

New math element of type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Σχόλια



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) μέθοδος

Δημιουργεί υπο- και ανωδείκτη στα δεξιά

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lower index on the right) |
| superscript | [System::String](../../../system/string/) | Superscript (upper index on the right) |

### Τιμή Επιστροφής

New math element of type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Σχόλια



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Δείτε επίσης

* Τυποποίηση [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Κλάση [IMathElement](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)