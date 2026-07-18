---
title: set_InterruptionToken()
second_title: Aspose.Slides για C++ API Αναφορά
description: Το διακριτικό για την παρακολούθηση αιτημάτων διακοπής.
type: docs
weight: 248
url: /el/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) μέθοδος

Το διακριτικό για την παρακολούθηση αιτημάτων διακοπής.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Παρατηρήσεις

Αυτό το διακριτικό διαχειρίζεται ολόκληρη διάρκεια ζωής του αντικειμένου [IPresentation](../../ipresentation/). Οποιαδήποτε μακράς διάρκειας λειτουργία, όπως η φόρτωση ή η αποθήκευση παρουσίασης, θα διακόπτεται με την κλήση της μεθόδου [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) του [InterruptionTokenSource](../../interruptiontokensource/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IInterruptionToken](../../iinterruptiontoken/)
* Κλάση [LoadOptions](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)