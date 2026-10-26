---
title: "System::StringExtra"
second_title: Aspose.Slides για C++ API Αναφορά
description: 
type: docs
weight: 911
url: /el/system.stringextra/
---
## Συναρτήσεις

| Συνάρτηση | Περιγραφή |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Συνενώνει πίνακα συμβολοσειρών. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Συνενώνει συμβολοσειρές. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Συνενώνει συμβολοσειρές. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Συνενώνει συμβολοσειρές. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Μετατρέπει πολλαπλά αντικείμενα σε συμβολοσειρά και συνενώνει τις προκύπτουσες συμβολοσειρές. Εξειδίκευση για τύπους [SmartPtr](../system/smartptr/). |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Μετατρέπει πολλαπλά αντικείμενα σε συμβολοσειρά και συνενώνει τις προκύπτουσες συμβολοσειρές. Εξειδίκευση για αριθμητικούς τύπους. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Μετατρέπει πολλαπλά αντικείμενα σε συμβολοσειρά και συνενώνει τις προκύπτουσες συμβολοσειρές. Εξειδίκευση για δομές και άλλους τύπους τιμής. |