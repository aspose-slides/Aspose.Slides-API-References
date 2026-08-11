---
title: "System::Collections::Generic::Details"
second_title: "مرجع API لـ Aspose.Slides للغة C++"
description: 
type: docs
weight: 352
url: /ar/system.collections.generic.details/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | مجموعة يمكن استخدامها بواسطة طريقتي الامتداد IEnumerable.Cast() و IEnumerable.OfType(). |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | مجموعة يمكن استخدامها بواسطة طريقة الامتداد IEnumerable.Select(). |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | عداد يمكن استخدامه بواسطة طريقة الامتداد IEnumerable.Cast(). |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | عداد يمكن استخدامه بواسطة طريقة الامتداد IEnumerable.OfType(). |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | عداد يمكن استخدامه بواسطة طريقة الامتداد IEnumerable.Select(). |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## البنى

| البنية | الوصف |
| --- | --- |
| [ComparerType](./comparertype/) | يقارن العناصر باستخدام معيار 'less'. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | يقارن العناصر باستخدام معيار 'less'. |
| [has_method_compareto](./has_method_compareto/) | يتحقق مما إذا كانت طريقة CompareTo موجودة في النوع المحدد. إذا كان كذلك، يرث std::true_type، وإلا يرث std::false_type. يمكن استخدامها في std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | يتحقق مما إذا كانت طريقة CompareTo(SharedPtr<T>) موجودة في النوع المحدد. إذا كان كذلك، يرث std::true_type، وإلا يرث std::false_type. يمكن استخدامها في std::enable_if. |
| [IsEqualExist](./isequalexist/) | يتحقق مما إذا كان النوع يوفر المشغل ==. |
## الدوال

| الدالة | الوصف |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | يتحقق مما إذا كان الفهرس خارج حدود الحاوية، مع استثناء حجم الحاوية. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | يتحقق مما إذا كان الفهرس خارج حدود الحاوية، مع استثناء حجم الحاوية. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | يتحقق مما إذا كان الفهرس خارج حدود الحاوية، مع تضمين حجم الحاوية. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | يتحقق مما إذا كان الفهرس خارج حدود الحاوية، مع تضمين حجم الحاوية. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | دالة مساعدة لتحديد ما إذا كانت الفئة المحددة لديها المشغل ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | دالة مساعدة لتحديد ما إذا كانت الفئة المحددة لديها المشغل ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | يحاول الحصول على العنصر الأول من المجموعة. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | يحاول الحصول على العنصر الأول من المجموعة الذي يحقق دالة التنبؤ. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | يحاول الحصول على العنصر الأخير من المجموعة. |
## تعريفات الأنواع

| تعريف النوع | الوصف |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | تعريف نوع وهمي للتحقق من وجود المشغل ==. |