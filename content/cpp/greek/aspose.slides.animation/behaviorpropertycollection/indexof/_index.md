---
title: IndexOf()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει τον δείκτη ενός συγκεκριμένου αντικειμένου στο IList.
type: docs
weight: 40
url: /el/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const μέθοδος

Καθορίζει τον δείκτη ενός συγκεκριμένου αντικειμένου στο [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | Το αντικείμενο που πρέπει να εντοπιστεί στο [IList](../../../system.collections.generic/ilist/). |

### Τιμή Επιστροφής

Ο δείκτης του *item* εάν βρεθεί στη λίστα· διαφορετικά, -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const μέθοδος

Καθορίζει τον δείκτη ενός συγκεκριμένου αντικειμένου βάσει της τιμής της ιδιότητας στο [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | Τιμή της ιδιότητας |

### Τιμή Επιστροφής

Ο δείκτης της ιδιότητας με την καθορισμένη τιμή

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IBehaviorProperty](../../ibehaviorproperty/)
* Κλάση [BehaviorPropertyCollection](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)