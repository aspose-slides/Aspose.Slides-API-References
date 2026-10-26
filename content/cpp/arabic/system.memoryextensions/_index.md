---
title: "System::MemoryExtensions"
second_title: مرجع API Aspose.Slides للـ C++
description: يوفر طرقًا ممتدة لعمليات الذاكرة على المقاطع والمصفوفات.
type: docs
weight: 625
url: /ar/system.memoryextensions/
---
يوفر أساليب امتداد لعمليات الذاكرة على spans ومصفوفات.

## الدوال

| الدالة | الوصف |
| --- | --- |
| [Span](../system/span/)\<T\> [AsSpan](./asspan/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, **int32_t**, **int32_t**) | يقوم بإنشاء span من مصفوفة. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [AsSpan](./asspan/)(const [String](../system/string/)\&, **int32_t**, **int32_t**) | يقوم بإنشاء span للقراءة فقط من سلسلة. |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TComparable\&) | يؤدي بحثًا ثنائيًا على span مُرتّب. |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | يؤدي بحثًا ثنائيًا على span مُرتّب باستخدام مقارنة مخصصة. |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const TComparable\&) | يؤدي بحثًا ثنائيًا على span مُرتّب قابل للتعديل. |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | يؤدي بحثًا ثنائيًا على span مُرتّب قابل للتعديل باستخدام مقارنة مخصصة. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد طول البادئة المشتركة بين spanين. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد طول البادئة المشتركة بين span قابل للتعديل و span للقراءة فقط. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | يحدد طول البادئة المشتركة بين spanين قابلين للتعديل. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | يحدد طول البادئة المشتركة بين spanين باستخدام مقارنة مساواة مخصصة. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | يحدد طول البادئة المشتركة بين span قابل للتعديل و span للقراءة فقط باستخدام مقارنة مساواة مخصصة. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | يحدد طول البادئة المشتركة بين spanين قابلين للتعديل باستخدام مقارنة مساواة مخصصة. |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | يتحقق مما إذا كان span للقراءة فقط يحتوي على قيمة معينة. |
| **bool** [Contains](./contains/)(const [Span](../system/span/)\<T\>\&, const T\&) | يتحقق مما إذا كان span قابل للتعديل يحتوي على قيمة معينة. |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | يتحقق مما إذا كان span أحرف يحتوي على span أحرف آخر وفق قواعد مقارنة محددة. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يتحقق مما إذا كان span للقراءة فقط يحتوي على أي من قيمتين. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | يتحقق مما إذا كان span للقراءة فقط يحتوي على أي من ثلاث قيم. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يتحقق مما إذا كان span قابل للتعديل يحتوي على أي من قيمتين. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | يتحقق مما إذا كان span قابل للتعديل يحتوي على أي من ثلاث قيم. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يتحقق مما إذا كان span للقراءة فقط يحتوي على أي قيمة من span آخر. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يتحقق مما إذا كان span قابل للتعديل يحتوي على أي قيمة من span للقراءة فقط. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | يتحقق مما إذا كان span للقراءة فقط يحتوي على أي عنصر باستثناء ثلاث قيم محددة. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | يتحقق مما إذا كان span قابل للتعديل يحتوي على أي عنصر باستثناء ثلاث قيم محددة. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يتحقق مما إذا كان span للقراءة فقط يحتوي على أي عنصر باستثناء قيمتين محددتين. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يتحقق مما إذا كان span قابل للتعديل يحتوي على أي عنصر باستثناء قيمتين محددتين. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | يتحقق مما إذا كان span للقراءة فقط يحتوي على أي عنصر باستثناء قيمة محددة. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | يتحقق مما إذا كان span قابل للتعديل يحتوي على أي عنصر باستثناء قيمة محددة. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يتحقق مما إذا كان span للقراءة فقط يحتوي على أي عنصر باستثناء العناصر الموجودة في span آخر. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يتحقق مما إذا كان span قابل للتعديل يحتوي على أي عنصر باستثناء العناصر الموجودة في span للقراءة فقط. |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يتحقق مما إذا كان span للقراءة فقط يحتوي على أي عنصر خارج النطاق المحدد. |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يتحقق مما إذا كان span قابل للتعديل يحتوي على أي عنصر خارج النطاق المحدد. |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يتحقق مما إذا كان span للقراءة فقط يحتوي على أي عنصر داخل النطاق المحدد. |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يتحقق مما إذا كان span قابل للتعديل يحتوي على أي عنصر داخل النطاق المحدد. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, [Span](../system/span/)\<T\>\&) | ينسخ العناصر من مصفوفة إلى span. |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | يحسب عدد مرات حدوث قيمة في span للقراءة فقط. |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحسب عدد مرات حدوث span داخل span آخر للقراءة فقط. |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const T\&) | يحسب عدد مرات حدوث قيمة واحدة في Span<T> |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحسب عدد مرات حدوث ReadOnlySpan<T> في Span<T> |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | يحدد ما إذا كان ReadOnlySpan<T> ينتهي بقيمة واحدة. |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد ما إذا كان ReadOnlySpan<T> ينتهي بـ ReadOnlySpan<T> آخر |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد ما إذا كان Span<T> ينتهي بـ ReadOnlySpan<T> |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | يحدد ما إذا كان ReadOnlySpan<T> ينتهي بـ Span<T> |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | يحدد ما إذا كان Span<T> ينتهي بـ Span<T> آخر |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | يحدد ما إذا كان ReadOnlySpan<char16_t> ينتهي بالقيمة المحددة باستخدام StringComparison. |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد فهرس قيمة ReadOnlySpan<T> في ReadOnlySpan<T> آخر. |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | يحدد فهرس قيمة واحدة في ReadOnlySpan<T> |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد فهرس قيمة ReadOnlySpan<T> في Span<T> |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | يحدد فهرس قيمة واحدة في Span<T> |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | يحدد فهرس قيمة ReadOnlySpan<char16_t> في ReadOnlySpan<char16_t> باستخدام StringComparison. |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يحدد فهرس أول حدوث لأي من قيمتين محددتين في ReadOnlySpan<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | يحدد فهرس أول حدوث لأي من ثلاث قيم محددة في ReadOnlySpan<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يحدد فهرس أول حدوث لأي من قيمتين محددتين في Span<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | يحدد فهرس أول حدوث لأي من ثلاث قيم محددة في Span<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد فهرس أول حدوث لأي قيمة من span في ReadOnlySpan<T> آخر |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد فهرس أول حدوث لأي قيمة من span في Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | يحدد فهرس أول عنصر لا يساوي القيمة المحددة في ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يحدد فهرس أول عنصر لا يساوي أيًا من قيمتين محددتين في ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | يحدد فهرس أول عنصر لا يساوي أيًا من ثلاث قيم محددة في ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | يحدد فهرس أول عنصر لا يساوي القيمة المحددة في Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يحدد فهرس أول عنصر لا يساوي أيًا من قيمتين محددتين في Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | يحدد فهرس أول عنصر لا يساوي أيًا من ثلاث قيم محددة في Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد فهرس أول عنصر لا يساوي أي قيمة في span من القيم. |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد فهرس أول عنصر لا يساوي أي قيمة في span من القيم داخل Span<T> |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يحدد فهرس أول عنصر خارج النطاق المحدد في ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يحدد فهرس أول عنصر خارج النطاق المحدد في Span<T> |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يحدد فهرس أول عنصر داخل النطاق المحدد في ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يحدد فهرس أول عنصر داخل النطاق المحدد في Span<T> |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد آخر حدوث لتسلسل داخل span. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | يحدد آخر حدوث لقيمة واحدة داخل span. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد آخر حدوث لتسلسل داخل span قابل للتعديل. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | يحدد آخر حدوث لقيمة واحدة داخل span قابل للتعديل. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | يحدد آخر حدوث لقيمة داخل span باستخدام مقارنة سلسلة محددة. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | يحدد آخر حدوث لأي من ثلاث قيم محددة داخل span. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | يحدد آخر حدوث لأي من ثلاث قيم محددة داخل span قابل للتعديل. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يحدد آخر حدوث لأي من قيمتين محددتين داخل span. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يحدد آخر حدوث لأي من قيمتين محددتين داخل span قابل للتعديل. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد آخر حدوث لأي قيمة من تسلسل داخل span. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد آخر حدوث لأي قيمة من تسلسل داخل span قابل للتعديل. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | يحدد آخر حدوث لأي قيمة من تسلسل قابل للتعديل داخل span قابل للتعديل. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | يبحث عن آخر ظهور لأي عنصر باستثناء ثلاث قيم محددة داخل نطاق. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | يبحث عن آخر ظهور لأي عنصر باستثناء ثلاث قيم محددة داخل نطاق قابل للتعديل. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يبحث عن آخر ظهور لأي عنصر باستثناء قيمتين محددتين داخل نطاق. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يبحث عن آخر ظهور لأي عنصر باستثناء قيمتين محددتين داخل نطاق قابل للتعديل. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | يبحث عن آخر ظهور لأي عنصر باستثناء قيمة محددة داخل نطاق. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | يبحث عن آخر ظهور لأي عنصر باستثناء قيمة محددة داخل نطاق قابل للتعديل. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يبحث عن آخر ظهور لأي عنصر باستثناء قيم من تسلسل داخل نطاق. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يبحث عن آخر ظهور لأي عنصر باستثناء قيم من تسلسل داخل نطاق قابل للتعديل. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | يبحث عن آخر ظهور لأي عنصر باستثناء قيم من تسلسل قابل للتعديل داخل نطاق قابل للتعديل. |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يبحث عن آخر ظهور لأي عنصر خارج النطاق المحدد داخل نطاق. |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يبحث عن آخر ظهور لأي عنصر خارج النطاق المحدد داخل نطاق قابل للتعديل. |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | يبحث عن آخر ظهور لأي عنصر داخل النطاق المحدد داخل نطاق. |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | يبحث عن آخر ظهور لأي عنصر داخل النطاق المحدد داخل نطاق قابل للتعديل. |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد ما إذا كان نطاقان للقراءة فقط يتقاطعان في الذاكرة دون حساب الإزاحة. |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد ما إذا كان [Span](../system/span/) و[ReadOnlySpan](../system/readonlyspan/) يتقاطعان في الذاكرة دون حساب الإزاحة. |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | يحدد ما إذا كان نطاقان للقراءة فقط يتقاطعان في الذاكرة ويحسب الإزاحة. |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | يحدد ما إذا كان [Span](../system/span/) و[ReadOnlySpan](../system/readonlyspan/) يتقاطعان في الذاكرة ويحسب الإزاحة. |
| void [Replace](./replace/)([Span](../system/span/)\<T\>\&, const T\&, const T\&) | يستبدل جميع حدوث القيمة بقيمة جديدة في [Span](../system/span/). |
| void [Replace](./replace/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ينسخ العناصر من المصدر إلى الوجهة، مستبدلاً القيم المحددة أثناء النسخ. |
| void [Reverse](./reverse/)([Span](../system/span/)\<T\>\&) | يعكس ترتيب العناصر في [Span](../system/span/) في مكانه. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يقارن نطاقين للقراءة فقط وفقًا للترتيب القاموسي. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يقارن [Span](../system/span/) و[ReadOnlySpan](../system/readonlyspan/) وفقًا للترتيب القاموسي. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | يقارن [ReadOnlySpan](../system/readonlyspan/) و[Span](../system/span/) وفقًا للترتيب القاموسي. |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد ما إذا كان نطاقان للقراءة فقط يحتويان على عناصر متماثلة بنفس الترتيب. |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يحدد ما إذا كان [Span](../system/span/) و[ReadOnlySpan](../system/readonlyspan/) يحتويان على عناصر متماثلة بنفس الترتيب. |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | يحدد ما إذا كان نطاقان للقراءة فقط يحتويان على عناصر متساوية باستخدام مُقارن مخصص. |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | يحدد ما إذا كان [Span](../system/span/) و[ReadOnlySpan](../system/readonlyspan/) يحتويان على عناصر متساوية باستخدام مُقارن مخصص. |
| void [Sort](./sort/)(const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | يرتب [Span](../system/span/) باستخدام مُقارن مخصص. |
| void [Sort](./sort/)([Span](../system/span/)\<T\>\&) | يرتب [Span](../system/span/) باستخدام المقارنة الافتراضية. |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | يرتب أزواج المفتاح والقيمة باستخدام مُقارن مخصص (المفاتيح والقيم تُرتب معًا) |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, [System::Comparison](../system/comparison/)\<TKey\>) | يرتب أزواج المفتاح والقيمة باستخدام وكيل مقارنة. |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&) | يرتب أزواج المفتاح والقيمة باستخدام المقارنة الافتراضية. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | يتحقق مما إذا كان النطاق يبدأ بالقيمة المحددة. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يتحقق مما إذا كان النطاق يبدأ بنطاق القيمة المحددة. |
| **bool** [StartsWith](./startswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يتحقق مما إذا كان النطاق القابل للتعديل يبدأ بنطاق القيمة للقراءة فقط المحددة. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | يتحقق مما إذا كان النطاق للقراءة فقط يبدأ بنطاق القيمة القابلة للتعديل المحددة. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | يتحقق مما إذا كان نطاق الأحرف يبدأ بنطاق القيمة المحدد باستخدام مقارنة السلسلة. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<[String](../system/string/)\>\&, const char16_t *) | يتحقق مما إذا كان نطاق السلسلة يبدأ بالمصفوفة الحرفية المحددة. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, T) | يقص العنصر المحدد من كلا طرفي نطاق مكتوب. |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, T) | يقص العنصر المحدد من كلا طرفي نطاق مكتوب قابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يقص العناصر المحددة من كلا طرفي نطاق مكتوب. |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يقص العناصر المحددة من كلا طرفي نطاق مكتوب قابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | يزيل أحرف المسافات الفارغة من كلا طرفي نطاق الأحرف. |
| [Span](../system/span/)\<char16_t\> [Trim](./trim/)([Span](../system/span/)\<char16_t\>\&) | يزيل أحرف المسافات الفارغة من كلا طرفي نطاق الأحرف القابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | يقص العنصر المحدد من نهاية نطاق مكتوب. |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const T\&) | يقص العنصر المحدد من نهاية نطاق مكتوب قابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يقص العناصر المحددة من نهاية نطاق مكتوب. |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يقص العناصر المحددة من نهاية نطاق مكتوب قابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | يزيل أحرف المسافات الفارغة من نهاية نطاق الأحرف. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&) | يزيل أحرف المسافات الفارغة من نهاية نطاق الأحرف القابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | يقص الحرف المحدد من نهاية نطاق الأحرف. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, char16_t) | يقص الحرف المحدد من نهاية نطاق الأحرف القابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | يقص الأحرف المحددة من نهاية نطاق الأحرف. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | يقص الأحرف المحددة من نهاية نطاق الأحرف القابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | يقص العنصر المحدد من بداية نطاق مكتوب. |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const T\&) | يقص العنصر المحدد من بداية نطاق مكتوب قابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يقص العناصر المحددة من بداية نطاق مكتوب. |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يقص العناصر المحددة من بداية نطاق مكتوب قابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | يزيل أحرف المسافات الفارغة من بداية نطاق الأحرف. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&) | يزيل أحرف المسافات الفارغة من بداية نطاق الأحرف القابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | يقص الحرف المحدد من بداية نطاق الأحرف. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, char16_t) | يقص الحرف المحدد من بداية نطاق الأحرف القابل للتعديل. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | يقص الأحرف المحددة من بداية نطاق الأحرف. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | يقص الأحرف المحددة من بداية نطاق الأحرف القابل للتعديل. |
| **int32_t** [CompareTo](./compareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | يقارن نطاقي أحرف وفقًا لقواعد مقارنة السلسلة المحددة. |
| **bool** [Equals](./equals/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | يقارن نطاقي قراءة فقط من نوع char16_t للتساوي باستخدام StringComparison. |
| **bool** [IsWhiteSpace](./iswhitespace/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | يتحقق مما إذا كان النطاق بأكمله يتكون فقط من أحرف المسافات الفارغة. |
| **int32_t** [ToLower](./tolower/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | يتحول الأحرف إلى حالة صغيرة باستخدام الثقافة المحددة. |
| **int32_t** [ToLowerInvariant](./tolowerinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | يتحول الأحرف إلى حالة صغيرة باستخدام الثقافة الثابتة. |
| **int32_t** [ToUpper](./toupper/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | يتحول الأحرف إلى حالة كبيرة باستخدام الثقافة المحددة. |
| **int32_t** [ToUpperInvariant](./toupperinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | يتحول الأحرف إلى حالة كبيرة باستخدام الثقافة الثابتة. |