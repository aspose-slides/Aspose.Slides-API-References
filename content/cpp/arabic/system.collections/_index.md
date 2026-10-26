---
title: "System::Collections"
second_title: مرجع API لـ Aspose.Slides للغة C++
description: 
type: docs
weight: 300
url: /ar/system.collections/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) من البتات التي يمكن الوصول إليها بواسطة الفهرس. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../system/makeobject/) فقط. لا تقوم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيؤدي إلى أخطاء زمان تشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة داخل مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [BitArrayPtr](./bitarrayptr/) | مؤشر إلى [BitArray](./bitarray/). هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالإشارة الثابتة. |
| [CollectionBase](./collectionbase/) | يقدم فئة أساسية تجريدية لمجموعة ذات نوع قوي. |
| [ICollection](./icollection/) | يعرّف واجهة مجموعة غير عامة. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) هي الواجهة الأساسية لجميع المجموعات غير العامة التي يمكن تعدادها. |
| [IEnumerator](./ienumerator/) | واجهة للعداد التي يمكن استخدامها للتكرار عبر بعض العناصر. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../system/makeobject/) فقط. لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء تشغيل و/أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة داخل مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | غلاف ينشئ تنفيذ [IEnumerator](./ienumerator/) غير عام فوق الـ Iterator العام [IEnumeratorImplRefType](./ienumeratorimplreftype/) - غلاف لأنواع المرجعية. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | غلاف ينشئ تنفيذ [IEnumerator](./ienumerator/) غير عام فوق الـ Iterator العام [IEnumeratorImplRefType](./ienumeratorimplreftype/) - غلاف لأنواع القيم. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) تمثّل مجموعة غير عامة من الكائنات التي يمكن الوصول إليها فرديًا بواسطة الفهرس. |
| [IListImplRefType](./ilistimplreftype/) | قالب يُنفّذ واجهة [System::Collections::IList](./ilist/) على كائن [System::Collections::Generic::List](../system.collections.generic/list/) تنفيذ للأنواع المرجعية. |
| [IListImplValueType](./ilistimplvaluetype/) | قالب يُنفّذ واجهة [System::Collections::IList](./ilist/) على كائن [System::Collections::Generic::List](../system.collections.generic/list/) تنفيذ للأنواع القيمية. |
| [IListWrapper](./ilistwrapper/) | واجهة لدعم التحويل من مجموعة عامة إلى مجموعة غير عامة. |
| [Invalidatable](./invalidatable/) | فئة تجعل من الممكن تتبع حالة سلالتها عبر كائنات [InvalidatableTracker](./invalidatabletracker/). |
| [InvalidatableTracker](./invalidatabletracker/) | فئة تُنفّذ متتبعي كائنات [Invalidatable](./invalidatable/). |