---
title: set_InterruptionToken()
second_title: Aspose.Slides για C++ API Αναφορά
description: Το διακριτικό για την παρακολούθηση των αιτημάτων διακοπής.
type: docs
weight: 248
url: /el/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) μέθοδος

Το διακριτικό για την παρακολούθηση των αιτημάτων διακοπής.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Παρατηρήσεις

Αυτό το διακριτικό διαχειρίζεται ολόκληρη τη διάρκεια ζωής του [IPresentation](../../ipresentation/). Οποιαδήποτε μακράς διάρκειας λειτουργία, όπως η φόρτωση ή η αποθήκευση παρουσίασης, θα διακοπεί μέσω κλήσης της [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) μέθοδος του [IInterruptionTokenSource](../../iinterruptiontokensource/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IInterruptionToken](../../iinterruptiontoken/)
* Κλάση [ILoadOptions](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)