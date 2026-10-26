---
title: get_InterruptionToken()
second_title: Αναφορά API Aspose.Slides για C++
description: Το διακριτικό για την παρακολούθηση αιτημάτων διακοπής.
type: docs
weight: 235
url: /el/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() μέθοδος


Το διακριτικό για την παρακολούθηση αιτημάτων διακοπής.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Σημειώσεις


Αυτό το διακριτικό διαχειρίζεται ολόκληρη τη διάρκεια ζωής της παρουσίας [IPresentation](../../ipresentation/). Οποιαδήποτε μακράς διάρκειας λειτουργία, όπως η φόρτωση ή η αποθήκευση μιας παρουσίασης, θα διακόπτεται μέσω της κλήσης της μεθόδου [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) του [InterruptionTokenSource](../../interruptiontokensource/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IInterruptionToken](../../iinterruptiontoken/)
* Κλάση [LoadOptions](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)