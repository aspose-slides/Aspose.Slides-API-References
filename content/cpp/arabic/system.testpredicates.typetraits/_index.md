---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides لمرجع API C++
description: 
type: docs
weight: 963
url: /ar/system.testpredicates.typetraits/
---
## الهياكل

| Struct | Description |
| --- | --- |
| [has_data_method](./has_data_method/) | يتحقق مما إذا كان النوع يمتلك الدالة data(). إذا كان كذلك، يرث std::true_type، وإلا يرث std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | تخصيص لنوع BitArray يوفّر نوع boost الذي لا يمكن الوصول إليه هناك. |
| [has_print_to_method](./has_print_to_method/) | يتحقق من وجود تحميل زائد للدالة PrintTo التي تقبل النوع المعطى كوسيط أول. إذا كان هناك تحميل زائد، يرث std::true_type، وإلا يرث std::false_type. |
| [IsCppContainer](./iscppcontainer/) | يتحقق مما إذا كان النوع المحدد حاوية على نمط STL. للقيام بذلك، يتحقق من وجود نوعَي الأعضاء iterator و const_iterator. إذا كان كلاهما موجودًا، يرث std::true_type، وإلا يرث std::false_type. |
| [IsEnumerable](./isenumerable/) | يتحقق مما إذا كان النوع يمتلك تخصيص [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) كأساس. إذا كان كذلك، يتم تعيين عضو القيمة إلى true، وإلا يتم تعيينه إلى false. |
| [LargestFPType](./largestfptype/) | يوفر اسمًا بديلًا لأطول نوع نقطة عائمة متوفر. يتجاهل الأنواع غير النقطة العائمة. |

## التعريفات النوعية

| Typedef | Description |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | يتحقق من أن **T1** عددية و **T2** نقطة عائمة، أو العكس. إذا كان كذلك، يتم تعيين عضو القيمة إلى true، وإلا فهو false. |
| [AnyOfDecimal](./anyofdecimal/) | يتحقق من أن أحد معاملات النوع على الأقل هو [System::Decimal](../system/decimal/). إذا كان كذلك، يتم تعيين عضو القيمة إلى true، وإلا فهو false. |
| [IsArray](./isarray/) | يتحقق مما إذا كان النوع تخصيصًا لـ [System::Array](../system/array/). إذا كان كذلك، يتم تعيين عضو القيمة إلى true، وإلا يتم تعيينه إلى false. |
| [IsList](./islist/) | يتحقق مما إذا كان النوع تخصيصًا لـ [System::Collections::Generic::List](../system.collections.generic/list/). إذا كان كذلك، يتم تعيين عضو القيمة إلى true، وإلا يتم تعيينه إلى false. |
| [BothArrayOrList](./botharrayorlist/) | يتحقق مما إذا كان كلا معاملَي النوع مصفوفات أو قوائم. إذا كان كذلك، يتم تعيين عضو القيمة إلى true، وإلا يتم تعيينه إلى false. |
| [BothEnumerable](./bothenumerable/) | يتحقق مما إذا كان كلا معاملَي النوع من IEnumerable. إذا كان كذلك، يتم تعيين عضو القيمة إلى true، وإلا يتم تعيينه إلى false. |