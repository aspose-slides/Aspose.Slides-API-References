---
title: "System::Collections::Generic"
second_title: مرجع API لـ Aspose.Slides للغة C++
description: 
type: docs
weight: 326
url: /ar/system.collections.generic/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [_KeyCollection](./_keycollection/) | مجموعة من مفاتيح [Dictionary](./dictionary/). تُشير إلى مجموعة ولا تُنسخ شيئًا. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [_KeyList](./_keylist/) | تنفيذ قائمة مفاتيح القاموس. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [_ValueCollection](./_valuecollection/) | مجموعة من قيم [Dictionary](./dictionary/). تُشير إلى مجموعة ولا تُنسخ شيئًا. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [_ValueList](./_valuelist/) | تنفيذ قائمة قيم القاموس. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [BaseDictionary](./basedictionary/) | تنفيذ كود مشترك لهياكل تشبه القاموس المتنوعة (مثلاً [Dictionary](./dictionary/), [SortedDictionary](./sorteddictionary/)). لا يجب استخدامه مباشرةً، باستثناء الوراثة عند تعريف الحاويات. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [BaseEnumerator](./baseenumerator/) | تعريف عداد لتغليف الأنواع على نمط STL لاستخدام بنمط C#. لا يفرض أي تأكيدات على بنية الحاوية باستثناء وجود مكرر متسلسل. يستخدم الدوال begin() و end(). يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [BaseKVCollection](./basekvcollection/) | يحمل كودًا مشتركًا لمجموعات المفاتيح أو القيم. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [BaseSet](./baseset/) |  |
| [Comparer](./comparer/) | يوفر فئة أساسية لتطبيقات الواجهة العامة [System.Collections.Generic.IComparer](./icomparer/). |
| [DefaultComparer](./defaultcomparer/) | فئة المقارن الافتراضية. تستخدم المُعامل < والمُعامل == لمقارنة القيم. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [Details_KeyNotFoundException](./details_keynotfoundexception/) |  |
| [Dictionary](./dictionary/) | إعلان مسبق للفئة [Dictionary](./dictionary/). |
| [DictionaryIterator](./dictionaryiterator/) | [Dictionary](./dictionary/) مؤشر الذي يوفر تدوين [KeyValuePair](./keyvaluepair/). |
| [DictionaryPtr](./dictionaryptr/) | فئة مؤشر [Dictionary](./dictionary/) مع تحميل المُعاملات. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت. |
| [EnumerableExt](./enumerableext/) |  |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/) | مؤشر يغلف المُعداد المُنشأ مسبقًا ويوجه جميع الاستدعاءات إليه. |
| [HashDictionary](./hashdictionary/) | قالب للفئة [HashDictionary](./hashdictionary/) (غير مُنفذ حاليًا). يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [HashSet](./hashset/) | إعلان مسبق للفئة [HashSet](./hashset/). |
| [HashSetPtr](./hashsetptr/) | مؤشر للاحتفاظ بمراجع [HashSet](./hashset/). هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت. |
| [ICollection](./icollection/) | واجهة لمجموعة من العناصر. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [IComparer](./icomparer/) | واجهة تقارن كائنين بمعنى أكبر-أكبر من أو يساوي أو أصغر. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [IDictionary](./idictionary/) | واجهة لحاويات شبيهة بالقاموس. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [IEnumerable](./ienumerable/) | واجهة كائن يوفر عدّادًا على العناصر المحتواة. |
| [IEnumerator](./ienumerator/) | واجهة عدّاد يمكن استخدامها للتجول عبر بعض العناصر. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [IEqualityComparer](./iequalitycomparer/) | واجهة توفر وسيلة لمقارنة كائنين للمساواة. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [IKVCollection](./ikvcollection/) | واجهة حاوية تحتوي على مفاتيح أو قيم الحاوية الشبيهة بالقاموس. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [IList](./ilist/) | واجهة حاوية مفهرسة للعناصر. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [ISet](./iset/) | واجهة مجموعة تحتوي على مجموعة من العناصر الفريدة. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [KeyIterator](./keyiterator/) | [Dictionary](./dictionary/) مؤشر الذي يوفر وصولًا إلى المفتاح. |
| [KeyValuePair](./keyvaluepair/) | زوج من المفتاح والقيمة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم الفئة [System::SmartPtr](../system/smartptr/) لإدارة كائنات هذا النوع. |
| [KVPairIterator](./kvpairiterator/) | مؤشر متكيف، يغلف std::pair إلى KVPair المتوقعة من [Dictionary](./dictionary/). |
| [LinkedList](./linkedlist/) | إعلان مسبق لـ [LinkedList](./linkedlist/). |
| [LinkedListNode](./linkedlistnode/) | عقدة من القائمة المرتبطة. تنفّذ غلافًا فوق مؤشر std::list المُغلف في القائمة المرتبطة. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [List](./list/) | إعلان مسبق لـ [List](./list/). |
| [ListExt](./listext/) | فئة [List](./list/) العامة التي تنفّذ واجهة [IListWrapper](../system.collections/ilistwrapper/). |
| [ListPtr](./listptr/) | مؤشر [List](./list/) مع مُعاملات الوصول. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت. |
| [Queue](./queue/) | إعلان مسبق لفئة [Queue](./queue/). |
| [QueuePtr](./queueptr/) | مؤشر [Queue](./queue/). هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت. |
| [ReverseEnumerator](./reverseenumerator/) | عدّاد يتجول عكسياً عبر الحاوية. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SimpleEnumerator](./simpleenumerator/) | فئة مؤشر للحاويات البسيطة التي تحتفظ بالعناصر مباشرةً باستخدام دوال rbegin() و rend(). يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SortedDictionary](./sorteddictionary/) | إعلان مسبق لنوع قاموس مرتب. |
| [SortedDictionaryPtr](./sorteddictionaryptr/) | مؤشر قاموس مرتب مع مُعاملات الوصول. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت. |
| [SortedList](./sortedlist/) | قائمة مرتبة تغلف بنية FlatMap. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المُعامل new، لأن ذلك سيتسبب في أخطاء زمن تشغيل أو عطل في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SortedListHelper](./sortedlisthelper/) | هذه الفئة المساعدة تُستخدم لإخفاء الدوال الافتراضية get_Keys و get_Values الواردة من واجهة [IDictionary](./idictionary/) واستبدالها بدوال ذات نوع إرجاع مختلف. |
| [SortedSet](./sortedset/) | إعلان مسبق للفئة [SortedSet](./sortedset/). |
| [SortedSetPtr](./sortedsetptr/) | مؤشر للاحتفاظ بمراجع [SortedSet](./sortedset/). هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت. |
| [Stack](./stack/) | إعلان مسبق للفئة [Stack](./stack/). |
| [StackPtr](./stackptr/) | مؤشر [Stack](./stack/). هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت. |
| [ValueIterator](./valueiterator/) | مؤشر [Dictionary](./dictionary/) الذي يوفر وصولًا إلى القيمة. |

## الهياكل

| الهيكل | الوصف |
| --- | --- |
| [ComparerAdapter](./compareradapter/) | مهايئ لاستخدام [IComparer](./icomparer/) داخل بيئة STL. يستخدم [IComparer](./icomparer/) إذا تم تعيينه؛ وإلا يستخدم المُعامل < (إذا كان متاحًا) أو يُعيد false (إذا لم يكن). |
| [DictionaryHashSelector](./dictionaryhashselector/) | محدد دالة التجزئة للفئة [Dictionary](./dictionary/). يستخدم هذا التنفيذ تجزئة STL في حال عدم توفر بديل. |
| [EqualityComparerAdapter](./equalitycompareradapter/) | مهايئ يجعل الاستخدام ممكنًا لـ [IEqualityComparer](./iequalitycomparer/) مع المجموعات والخوارزميات على نمط STL. يستخدم [IEqualityComparer](./iequalitycomparer/) إذا تم تعيينه. إذا لم يُعيّن، يستخدم المُعامل == أو [Object::Equals](../system/object/equals/) أو T::Equals، أيًا كان متاحًا. |
| [EqualityComparerHashAdapter](./equalitycomparerhashadapter/) | مهايئ لاستخدام [IEqualityComparer](./iequalitycomparer/) للتجزئة. يستخدم كائن المقارن إذا تم تعيينه؛ وإلا يستخدم طريقة التجزئة المتاحة المختارة باستخدام بنية [DictionaryHashSelector](./dictionaryhashselector/). |

## الدوال

| الدالة | الوصف |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | يقارن زوجين من المفتاح والقيمة باستخدام دلالة 'equals'. يستخدم المُعامل == أو طريقة EqualsTo لكل من المفاتيح والقيم، حسب ما تم تعريفه. |
| **bool** [operator!=](./operator_not_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | يقارن زوجين من المفتاح والقيمة باستخدام دلالة 'equals' العكسية. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | يدرج البيانات في الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | يدرج البيانات في الدفق. |

## التعريفات النوعية

| التعريف النوعي | الوصف |
| --- | --- |
| [KeyNotFoundException](./keynotfoundexception/) |  |