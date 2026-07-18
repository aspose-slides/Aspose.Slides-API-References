---
title: MathematicalText()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Προεπιλεγμένος κατασκευαστής (create String::Empty Value)"
type: docs
weight: 40
url: /el/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() Κατασκευαστής

Προεπιλεγμένος κατασκευαστής (create String::Empty Value)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) Κατασκευαστής

Δημιουργήστε [MathText](../../) με ενιαίο σύμβολο

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathSymbol | char16_t | ενιαίο σύμβολο |
## Παρατηρήσεις

Παράδειγμα:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) Κατασκευαστής

Δημιουργήστε [MathematicalText](../) από κείμενο

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | τιμή κειμένου |
## Παρατηρήσεις

Παράδειγμα:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) Κατασκευαστής

Δημιουργήστε [MathematicalText](../) από κείμενο και ρυθμίσεις μορφοποίησης κειμένου

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | τιμή κειμένου |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | ρυθμίσεις μορφοποίησης κειμένου |
## Παρατηρήσεις

Παράδειγμα:
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [MathematicalText](../)
* Κλάση [String](../../../system/string/)
* Κλάση [IPortionFormat](../../../aspose.slides/iportionformat/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)