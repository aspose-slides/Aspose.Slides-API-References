---
title: System
second_title: مرجع API Aspose.Slides للغة C++
description: 
type: docs
weight: 274
url: /ar/system/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [Activator](./activator/) | يحتوي على طرق لإنشاء أنواع من الكائنات. |
| [Array](./array/) | فئة تمثل هيكل بيانات المصفوفة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالتين [System::MakeArray()](./makearray/) و[System::MakeObject()](./makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيتسبب في أخطاء وقت تشغيل و/أو أعطال التحقق. دائماً قم بلف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل. |
| [ArrayBase](./arraybase/) | البديل لفئة [System.Array](./array/) (فئة أساسية مجردة لجميع المصفوفات) قد تُملأ بالوظائف عند الطلب. |
| [ArraySegment](./arraysegment/) | يمثل قطاعاً من المصفوفة أحادية البُعد. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [Attribute](./attribute/) | فئة أساسية للسمات المخصصة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيتسبب في أخطاء وقت تشغيل و/أو أعطال التحقق. دائماً قم بلف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل. |
| [BitConverter](./bitconverter/) | يحتوي على طرق تقوم بتحويل تسلسل من البايتات إلى نوع قيمة والعكس. هذا نوع ثابت لا يحتوي على خدمات للنسخ. يجب ألا تنشئ أي مثيلات له بأي طريقة. |
| [Boolean](./boolean/) | فئة تحتفظ بالعضويات الثابتة من نوع [System.Boolean](./boolean/) .[Net](../system.net/). |
| [BoxedEnum](./boxedenum/) | يمثل قيمة تعداد مغلّفة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيتسبب في أخطاء وقت تشغيل و/أو أعطال التحقق. دائماً قم بلف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل. |
| [BoxedValue](./boxedvalue/) | يمثل قيمة مغلّفة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت تشغيل و/أو أعطال التحقق. دائماً قم بلف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل. |
| [BoxedValue< ValueTuple< Args... > >](./boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/) | الإصدار المغلق من مجموعة القيم. |
| [BoxedValueBase](./boxedvaluebase/) | فئة أساسية تعرف واجهة وتُنفّذ بعض الطرق الأساسية لفئة مُشتقة تمثل قيمة مغلّفة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت تشغيل و/أو أعطال التحقق. دائماً قم بلف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل. |
| [Buffer](./buffer/) | يحتوي على طرق تُعالج مصفوفات البايت الخام. هذا نوع ثابت لا يحتوي على خدمات للنسخ. يجب ألا تُنشئ أي مثيلات له بأي وسيلة. |
| [Byte](./byte/) | يحتوي على طرق للتعامل مع عدد صحيح غير موقع 8-بت. |
| [Char](./char/) | يوفر طرقاً لمعالجة الأحرف الممثلة كوحدات شفرة UTF-16. هذا نوع ثابت لا يحتوي على خدمات للنسخ. يجب ألا تُنشئ أي مثيلات له بأي وسيلة. |
| [Comparison](./comparison/) | يمثل مؤشرًا إلى الطريقة التي تقارن كائنين من نفس النوع. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [Console](./console/) | يوفر طرقاً لإخراج البيانات إلى تدفق الإخراج القياسي. هذا نوع ثابت لا يحتوي على خدمات للنسخ. يجب ألا تُنشئ أي مثيلات له بأي وسيلة. |
| [ConsoleOutput](./consoleoutput/) | يمثل تدفق الإخراج القياسي. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت تشغيل و/أو أعطال التحقق. دائماً قم بلف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل. |
| [DateTime](./datetime/) | يمثل قيمة تاريخ ووقت محددة على خط الزمن. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [DateTimeOffset](./datetimeoffset/) | يحتوي على التاريخ والوقت بالنسبة للتوقيت العالمي المتناغم. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت تشغيل و/أو أعطال التحقق. دائماً قم بلف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل. |
| [DBNull](./dbnull/) | يمثل قيمة غير موجودة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت تشغيل و/أو أعطال التحقق. دائماً قم بلف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل. |
| [Decimal](./decimal/) | يمثل رقمًا عشريًا. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) تنفيذ فئة. يسمح بإعلان تخصيصات BoxingValue دون تكرار الشيفرة المشتركة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت تشغيل و/أو أعطال التحقق. دائماً قم بلف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل. |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | يمثل مؤشرًا إلى دالة أو طريقة أو كائن دالة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [Details_AggregateException](./details_aggregateexception/) | يمثل استثناءً يحتوي على عدة استثناءات داخلية. |
| [Details_ApplicationException](./details_applicationexception/) | فئة أساسية للفئات التي تمثل استثناءات التطبيق (بدلاً من نظام). لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة ApplicationException بدلًا من ذلك. لا تُلفّ مثيلات فئة ApplicationException في [System::SmartPtr](./smartptr/). |
| [Details_ArgumentException](./details_argumentexception/) | ArgumentException يُرمى عندما يكون аргумент المُمرَّ إلى طريقة مُستدَعى غير صالح. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة ArgumentException بدلاً من ذلك. لا تُلفّ مثيلات فئة ArgumentException في [System::SmartPtr](./smartptr/). |
| [Details_ArgumentNullException](./details_argumentnullexception/) |  |
| [Details_ArgumentOutOfRangeException](./details_argumentoutofrangeexception/) | ArgumentOutOfRangeException يُرمى عندما تُمرَّ إلى طريقة مُستدَعى حجة خارج النطاق المتوقع للقيم. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة ArgumentOutOfRangeException بدلاً من ذلك. لا تُلفّ مثيلات فئة ArgumentOutOfRangeException في [System::SmartPtr](./smartptr/). |
| [Details_ArithmeticException](./details_arithmeticexception/) | ArithmeticException يُرمى عندما يحدث خطأ أثناء تنفيذ عمليات حسابية أو تحويلات أو عمليات تحويل صريحة. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة ArithmeticException بدلاً من ذلك. لا تُلفّ مثيلات فئة ArithmeticException في [System::SmartPtr](./smartptr/). |
| [Details_BadImageFormatException](./details_badimageformatexception/) | الاستثناء الذي يُرمى عندما تكون صورة ملف مكتبة الربط الديناميكية (DLL) أو برنامج تنفيذي غير صالحة. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة BadImageFormatException بدلاً من ذلك. لا تُلفّ مثيلات فئة BadImageFormatException في [System::SmartPtr](./smartptr/). |
| [Details_DataMisalignedException](./details_datamisalignedexception/) |  |
| [Details_DivideByZeroException](./details_dividebyzeroexception/) | DivideByZeroException يُرمى عندما يُحاول إجراء عملية قسمة على 0 في عملية حسابية. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة DivideByZeroException بدلاً من ذلك. لا تُلفّ مثيلات فئة DivideByZeroException في [System::SmartPtr](./smartptr/). |
| [Details_Exception](./details_exception/) | يمثل استثناءً. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة Exception بدلاً من ذلك. لا تُلفّ مثيلات فئة Exception في [System::SmartPtr](./smartptr/). |
| [Details_ExceptionWithErrorCode](./details_exceptionwitherrorcode/) | فئة القالب لاستثناء يحتوي على رمز خطأ. |
| [Details_ExceptionWithFilename](./details_exceptionwithfilename/) | فئة القالب لاستثناء يحتوي على اسم ملف. |
| [Details_ExecutionEngineException](./details_executionengineexception/) | ExecutionEngineException موجود لأسباب التوافق فقط. |
| [Details_FormatException](./details_formatexception/) | FormatException يُرمى عندما يكون تنسيق حجة الطريقة غير صالح. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة FormatException بدلاً من ذلك. لا تُلفّ مثيلات فئة FormatException في [System::SmartPtr](./smartptr/). |
| [Details_IndexOutOfRangeException](./details_indexoutofrangeexception/) | IndexOutOfRangeException يُرمى عندما يُحاول الوصول إلى عنصر من مجموعة باستخدام فهرس خارج حدودها. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة IndexOutOfRangeException بدلاً من ذلك. لا تُلفّ مثيلات فئة IndexOutOfRangeException في [System::SmartPtr](./smartptr/). |
| [Details_InvalidCastException](./details_invalidcastexception/) | InvalidCastException يُرمى عندما تُحاول عملية تحويل صريحة غير صالحة. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة InvalidCastException بدلاً من ذلك. لا تُلفّ مثيلات فئة InvalidCastException في [System::SmartPtr](./smartptr/). |
| [Details_InvalidOperationException](./details_invalidoperationexception/) | الاستثناء الذي يُرمى عندما تُستدعى طريقة على كائن في حالة غير متسقة مع هذا الاستدعاء. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة InvalidOperationException بدلاً من ذلك. لا تُلفّ مثيلات فئة InvalidOperationException في [System::SmartPtr](./smartptr/). |
| [Details_InvalidProgramException](./details_invalidprogramexception/) | InvalidProgramException موجود لأسباب التوافق فقط. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة InvalidProgramException بدلاً من ذلك. لا تُلفّ مثيلات فئة InvalidProgramException في [System::SmartPtr](./smartptr/). |
| [Details_InvalidTimeZoneException](./details_invalidtimezoneexception/) | InvalidTimeZoneException يُرمى عندما تكون معلومات المنطقة الزمنية غير صالحة. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة InvalidTimeZoneException بدلاً من ذلك. لا تُلفّ مثيلات فئة InvalidTimeZoneException في [System::SmartPtr](./smartptr/). |
| [Details_MemberAccessException](./details_memberaccessexception/) | MemberAccessException يُرمى عندما يُحاول الوصول إلى عضو غير موجود في فئة أو عندما يكون الوصول إلى العضو غير مسموح به. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة MemberAccessException بدلاً من ذلك. لا تُلفّ مثيلات فئة MemberAccessException في [System::SmartPtr](./smartptr/). |
| [Details_MethodAccessException](./details_methodaccessexception/) | MemberAccessException يُرمى عندما يُحاول الوصول إلى طريقة غير موجودة أو عندما يكون الوصول إلى الطريقة غير مسموح به. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة MethodAccessException بدلاً من ذلك. لا تُلفّ مثيلات فئة MethodAccessException في [System::SmartPtr](./smartptr/). |
| [Details_NotImplementedException](./details_notimplementedexception/) | NotImplementedException يُرمى عندما تُستدعى طريقة غير مُنفذة وتعمل كقالب (stub). لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة NotImplementedException بدلاً من ذلك. لا تُلفّ مثيلات فئة NotImplementedException في [System::SmartPtr](./smartptr/). |
| [Details_NotSupportedException](./details_notsupportedexception/) | NotSupportedException يُرمى عندما لا تُدعم الطريقة المستدعاة أو عندما لا يُدعم العملية المحاولة على تدفق. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة NotSupportedException بدلاً من ذلك. لا تُلفّ مثيلات فئة NotSupportedException في [System::SmartPtr](./smartptr/). |
| [Details_NullReferenceException](./details_nullreferenceexception/) | NullReferenceException يُرمى عندما يُحاول إلغاء الإشارة إلى مرجع فارغ. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة NullReferenceException بدلاً من ذلك. لا تُلفّ مثيلات فئة NullReferenceException في [System::SmartPtr](./smartptr/). |
| [Details_ObjectDisposedException](./details_objectdisposedexception/) | ObjectDisposedException يُرمى عندما تُستدعى طريقة على كائن تم التخلص منه. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة ObjectDisposedException بدلاً من ذلك. لا تُلفّ مثيلات فئة ObjectDisposedException في [System::SmartPtr](./smartptr/). |
| [Details_OperationCanceledException](./details_operationcanceledexception/) | OperationCanceledException يُرمى في خيط عند إلغاء عملية كان الخيط ينفذها. لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة OperationCanceledException بدلاً من ذلك. لا تُلفّ مثيلات فئة OperationCanceledException في [System::SmartPtr](./smartptr/). |
| [Details_OutOfMemoryException](./details_outofmemoryexception/) |  |
| [Details_OverflowException](./details_overflowexception/) | OverflowException يُرمى عندما تؤدي عملية إلى تجاوز سعة (overflow). لا تقم بإنشاء مثيلات لهذه الفئة يدوياً. استخدم فئة OverflowException بدلاً من ذلك. لا تُلفّ مثيلات فئة OverflowException في [System::SmartPtr](./smartptr/). |
| [Details_PlatformNotSupportedException](./details_platformnotsupportedexception/) | يرمى استثناء PlatformNotSupportedException عندما لا تعمل ميزة على منصة معينة. لا تُنشئ أمثلة من هذه الفئة يدويًا. استخدم فئة PlatformNotSupportedException بدلاً من ذلك. لا تُغلّف كائنات فئة PlatformNotSupportedException داخل [System::SmartPtr](./smartptr/). |
| [Details_RankException](./details_rankexception/) | يرمى استثناء RankException عندما يُمرَّر إلى طريقة مصفوفة ذات عدد أبعاد يختلف عن المتوقع. لا تُنشئ أمثلة من هذه الفئة يدويًا. استخدم فئة RankException بدلاً من ذلك. لا تُغلّف كائنات فئة RankException داخل [System::SmartPtr](./smartptr/). |
| [Details_StackOverflowException](./details_stackoverflowexception/) | يرمى استثناء StackOverflowException عندما يفيض مكدس التنفيذ للخط. لا تُنشئ أمثلة من هذه الفئة يدويًا. استخدم فئة StackOverflowException بدلاً من ذلك. لا تُغلّف كائنات فئة StackOverflowException داخل [System::SmartPtr](./smartptr/). |
| [Details_SystemException](./details_systemexception/) | فئة أساسية للفئات التي تمثل استثناءات نظامية (وليس تطبيقية). لا تُنشئ أمثلة من هذه الفئة يدويًا. استخدم فئة SystemException بدلاً من ذلك. لا تُغلّف كائنات فئة SystemException داخل [System::SmartPtr](./smartptr/). |
| [Details_TimeoutException](./details_timeoutexception/) | يدل استثناء TimeoutException على انتهاء الوقت المخصص لعملية أو إجراء. لا تُنشئ أمثلة من هذه الفئة يدويًا. استخدم فئة TimeoutException بدلاً من ذلك. لا تُغلّف كائنات فئة TimeoutException داخل [System::SmartPtr](./smartptr/). |
| [Details_TimeZoneNotFoundException](./details_timezonenotfoundexception/) | يرمى استثناء TimeZoneNotFoundException عندما لا يُعثر على معلومات المنطقة الزمنية. لا تُنشئ أمثلة من هذه الفئة يدويًا. استخدم فئة TimeZoneNotFoundException بدلاً من ذلك. لا تُغلّف كائنات فئة TimeZoneNotFoundException داخل [System::SmartPtr](./smartptr/). |
| [Details_TypeInitializationException](./details_typeinitializationexception/) |  |
| [Details_UnauthorizedAccessException](./details_unauthorizedaccessexception/) | يرمى استثناء UnauthorizedAccessException عندما يرفض نظام التشغيل الوصول بسبب خطأ إدخال/إخراج أو خطأ أمان. لا تُنشئ أمثلة من هذه الفئة يدويًا. استخدم فئة UnauthorizedAccessException بدلاً من ذلك. لا تُغلّف كائنات فئة UnauthorizedAccessException داخل [System::SmartPtr](./smartptr/). |
| [Details_UriFormatException](./details_uriformatexception/) | يرمى استثناء UriFormatException عندما يكون تنسيق URI غير صالح. لا تُنشئ أمثلة من هذه الفئة يدويًا. استخدم فئة UriFormatException بدلاً من ذلك. لا تُغلّف كائنات فئة UriFormatException داخل [System::SmartPtr](./smartptr/). |
| [DynamicWeakPtr](./dynamicweakptr/) | فئة المؤشر الذكي التي تتعقّب أوضاع المؤشر للوسائط القالبية للكائن المخزن وتحدّثها بعد كل إسناد. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت. |
| [EnumValues](./enumvalues/) | يوفر معلومات ميتا حول ثوابت التعداد لنوع enum **E**. |
| [EnumValuesBase](./enumvaluesbase/) | فئة أساسية لفئة تمثل معلومات ميتا لنوع التعداد. |
| [EventArgs](./eventargs/) | الفئة الأساسية للفئات التي تمثل سياقًا يُمرَّر إلى المشتركين في الحدث عندما يتم تشغيل الحدث. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [ExceptionWrapper](./exceptionwrapper/) | قالب يمثل غلافًا للاستثناءات المشتقة من فئة Exception. |
| [FlagsAttribute](./flagsattribute/) | يشير إلى أنه يمكن التعامل مع التعداد كحقل بت؛ أي مجموعة من. |
| [Func](./func/) | مندوب الدالة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [GC](./gc/) | يمثل جمع القمامة المُحاكى والذي يعمل كدَعْم لا يفعل شيئًا فعليًا. هذا نوع ثابت لا يقدم خدمات مثيلات. يجب ألا تُنشئ أمثلة منه بأي وسيلة. |
| [Guid](./guid/) | يمثل معرفًا عالميًا فريدًا (GUID). يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [IAsyncResult](./iasyncresult/) | يمثل حالة عملية غير متزامنة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [ICloneable](./icloneable/) | يعرّف طريقة تتيح استنساخ الكائن - إنشاء نسخة من كائن. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [IComparable](./icomparable/) | يعرّف طريقة تقارن كائنين. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [IConvertible](./iconvertible/) | يعرّف طرقًا تحول قيمة النوع المرجعي أو القيمي المنفّذ إلى نوع تشغيل لغة مشتركة له قيمة مكافئة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [ICustomFormatter](./icustomformatter/) | يعرّف طريقة تُجري تنسيقًا مخصَّصًا لتمثيل سلسلة لقيمة يمثلها الكائن المحدد. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [IDisposable](./idisposable/) | يعرّف طريقة تُفرج عن الموارد التي تملكها الكائن الحالي. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [IEquatable](./iequatable/) | يعرّف طريقة تحدد مساواة كائنين. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [IFormatProvider](./iformatprovider/) | يعرّف طريقة تُوفر معلومات تنسيق. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [IFormattable](./iformattable/) | يعرّف طريقة تُنسق قيمة الكائن الحالي باستخدام سلسلة التنسيق المحددة ومُوفِّر التنسيق. |
| [Index](./index/) | يمثل فهرسًا داخل مجموعة. يمكن أن يكون الفهرس من البداية أو من النهاية. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [Int16](./int16/) | يحتوي على طرق للعمل مع عدد صحيح 16-بت. |
| [Int32](./int32/) | يحتوي على طرق للعمل مع عدد صحيح 32-بت. |
| [Int64](./int64/) | يحتوي على طرق للعمل مع عدد صحيح 64-بت. |
| [LockContext](./lockcontext/) | كائن حارس ينفّذ عبارة C# lock(). |
| [MarshalByRefObject](./marshalbyrefobject/) | يوفر وصولًا إلى الكائنات عبر حدود نطاق التطبيق في التطبيقات التي تدعم الاستدعاء عن بُعد. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | يمثل مجموعة من المندوبين. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [Nullable](./nullable/) | إعلان أمامي. |
| [NullableUtils](./nullableutils/) | يمثل الفئة الثابتة C# [System.Nullable](./nullable/) (بدون وسائط نوعية). لا يمكن استخدام الاسم الأصلي بسبب عدم القدرة على تحميل قوالب الفئات في C++. يدعم نوعًا قيميًا يمكن تعيينه كقيمة فارغة. لا يمكن وراثة هذه الفئة. |
| [Object](./object/) | فئة أساسية تمكّن من استخدام الطرق المتاحة لفئة [System.Object](./object/) في C#. يجب أن ترث جميع الفئات غير التافهة المستخدمة في البيئة المترجمة هذه الفئة. |
| [ObjectExt](./objectext/) | يوفر طرقًا ثابتة تحاكي طرق C# [Object](./object/) المستدعاة لأنواع C++ غير كائنية (سلاسل، أعداد، إلخ). هذا نوع ثابت لا يقدم خدمات مثيلات. يجب ألا تُنشئ أمثلة منه بأي وسيلة. |
| [ObjectType](./objecttype/) | يوفر طرقًا ثابتة تنفّذ getters لأنواع الكائن. هذا نوع ثابت لا يقدم خدمات مثيلات. يجب ألا تُنشئ أمثلة منه بأي وسيلة. |
| [OperatingSystem](./operatingsystem/) | يمثل نظام تشغيل معين ويقدم معلومات حوله. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [Random](./random/) | يمثل مولِّد أعداد عشوائية مزيفة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة داخل مؤشر [System::SmartPtr](./smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [Range](./range/) | يمثل نطاقًا ببدء ونهاية فهرس. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [ReadOnlySpan](./readonlyspan/) | إحالة للاستخدام داخل فئة [Span](./span/). |
| [ScopedCulture](./scopedculture/) | يمثل ثقافة تُستخدم ضمن النطاق. |
| [SmartPtr](./smartptr/) | فئة مؤشر لتغليف الأنواع التي تُخصص على الكومة. استخدمها لإدارة الذاكرة للفئات التي ترث [Object](./object/). يتبع هذا النوع من المؤشرات دلالات المؤشر المتطفل. يتم تخزين عداد المرجع إما في [Object](./object/) نفسها أو في بنية عداد مرتبطة بشدة بكيان [Object](./object/). على أي حال، جميع كائنات [SmartPtr](./smartptr/) تشكل مجموعة ملكية واحدة بغض النظر عن طريقة إنشائها، وهو خلاف سلوك فئة std::shared_ptr. تحويل مؤشر خام إلى [SmartPtr](./smartptr/) آمن طالما توجد كائنات [SmartPtr](./smartptr/) أخرى تحتفظ بمراجع مشتركة إلى نفس الكائن. يمكن أن يكون كائن فئة [SmartPtr](./smartptr/) في إحدى حالتين: مؤشر مشترك ومؤشر ضعيف. للحفاظ على بقاء الكائن حيًا، يجب أن يكون عدد المراجع المشتركة إليه موجبة. يمكن استخدام كل من المؤشرات الضعيفة والمشتركة للوصول إلى الكائن المشار إليه (لإستدعاء الطرق، قراءة أو كتابة الحقول، إلخ)، لكن المؤشرات الضعيفة لا تشارك في عدّ مراجع المؤشر المشترك. يتم حذف [Object](./object/) عندما يتم تدمير آخر مؤشر 'مشترك' [SmartPtr](./smartptr/) إليه. لذا، تأكد من عدم حدوث ذلك عندما لا توجد مؤشرات [SmartPtr](./smartptr/) مشتركة أخرى إلى الكائن، مثل أثناء إنشاء الكائن أو تدميره. استخدم كائنات الحماية System::Object::ThisProtector (في شفرة C++) أو السمة CppCTORSelfReference أو CppSelfReference (في شفرة C# المترجمة) لإصلاح هذه المشكلة. بالمثل، تأكد من كسر مراجع الحلقة باستخدام فئة المؤشر [System::WeakPtr](./weakptr/) أو وضع المؤشر [System::SmartPtrMode::Weak](./smartptrmode/) (في شفرة C++) أو السمة CppWeakPtr (في شفرة C# المترجمة). إذا كان كائنان أو أكثر يشيران إلى بعضهما باستخدام مؤشرات 'مشتركة'، فلن يتم حذفهما أبدًا. إذا كان يجب تغيير نوع المؤشر (ضعيف أو مشترك) أثناء التنفيذ، استخدم طريقة [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) أو فئة [System::DynamicWeakPtr](./dynamicweakptr/). فئة [SmartPtr](./smartptr/) لا تحتوي على أي طرق افتراضية. يجب أن تورثها فقط إذا كنت تُنشئ استراتيجية إدارة ذاكرة خاصة بك. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع const. |
| [SmartPtrInfo](./smartptrinfo/) | فئة خدمة لاختبار وتعديل محتويات [SmartPtr](./smartptr/) دون معرفة النوع النهائي. تُستَخدم لجمع القمامة واكتشاف مراجع الحلقات، إلخ. فكر فيها كـ 'مؤشر إلى مؤشر'. لا يمكننا استخدام نوع قاعدة [SmartPtr](./smartptr/) لأنه لا يمتلك أي نوع أساسي؛ بدلاً من ذلك، نستخدم هذه الفئة 'المعلومات'. |
| [Span](./span/) | يمثل منطقة متصلة من الذاكرة العشوائية مماثلة لـ std::span في C++20. |
| [String](./string/) | فئة [String](./string/) تُستخدم عبر المكتبة. هي بديل لـ C# [System.String](./string/) عند ترجمة الشيفرة. لأسباب تحسين الأداء، لا يُعتبر فئة فرعية من [Object](./object/). يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبدًا فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [StringComparer](./stringcomparer/) | يقارن السلاسل باستخدام أوضاع مقارنة مختلفة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام عامل new، لأنه سيسبب أخطاءً في وقت التشغيل و/أو أعطالاً في التحقق. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [StringHashCompiletime](./stringhashcompiletime/) | فئة مساعدة تولد قيمة تجزئة من c-string. |
| [TimeSpan](./timespan/) | يمثل فترة زمنية. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [TimeZone](./timezone/) | يمثل نطاقًا زمنيًا. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام عامل new، لأنه سيسبب أخطاءً في وقت التنفيذ و/أو أعطالًا في التحقق. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [TimeZoneInfo](./timezoneinfo/) | يمثل معلومات تصف نطاقًا زمنيًا معينًا. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام عامل new، لأنه سيسبب أخطاءً في وقت التنفيذ و/أو أعطالًا في التحقق. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [Tuple](./tuple/) | فئة تمثل بنية بيانات tuple. الحد الأقصى لعدد العناصر هو 8. |
| [TupleFactory](./tuplefactory/) | توفر طرقًا ثابتة لإنشاء كائنات tuple. |
| [TypeInfo](./typeinfo/) | يمثل نوعًا معينًا ويوفر معلومات حوله. |
| [Uri](./uri/) | معرف مورد موحد. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام عامل new، لأنه سيسبب أخطاءً في وقت التنفيذ و/أو أعطالًا في التحقق. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [UriBuilder](./uribuilder/) | يوفر طرقًا لإنشاء وتعديل معرفات الموارد العالمية (URIs). يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام عامل new، لأنه سيسبب أخطاءً في وقت التنفيذ و/أو أعطالًا في التحقق. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [UriParser](./uriparser/) | يُستخدم لتحليل مخطط URI جديد. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](./makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام عامل new، لأنه سيسبب أخطاءً في وقت التنفيذ و/أو أعطالًا في التحقق. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](./smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [UriShim](./urishim/) | فئة خدمة. |
| [ValueTuple](./valuetuple/) | فئة تمثل بنية بيانات [ValueTuple](./valuetuple/). |
| [ValueType](./valuetype/) | فئة أساسية للأنواع القيمة التي تضم وراثة [Object](./object/) مُختصرة لأسباب الأداء. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [Version](./version/) | يمثل رقم إصدار. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | فئة فرعية من [System::SmartPtr](./smartptr/) التي تضبط نفسها على الوضع الضعيف عند الإنشاء. يرجى ملاحظة أن هذه الفئة لا تضمن أن يبقى مثيلها دائمًا في الوضع الضعيف لأن [set_Mode()](./smartptr/set_mode/) لا يزال قابلًا للوصول. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع const. |
| [WeakReference< T >](./weakreference_tmpl_t__end_tmpl/) | يمثل مرجعًا ضعيفًا، يُشير إلى كائن مع السماح بحذف ذلك الكائن. |
| [WeakReference<>](./weakreference_tmpl_end_tmpl/) | يمثل مرجعًا ضعيفًا، يُشير إلى كائن مع السماح بحذف ذلك الكائن. |

## Structures

| الهيكل | الوصف |
| --- | --- |
| [CastResult](./castresult/) | سحر القالب لاشتقاق نتائج التحويل. |
| [CollectionAssertHelper](./collectionasserthelper/) | واجهة برمجة تطبيقات مساعدة للعمليات المتعلقة بالمجموعات. |
| [Convert](./convert/) | البنية التي تحتوي على طرق تُجري تحويل قيم من نوع إلى قيم من نوع آخر. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [Double](./double/) | يحتوي على طرق للعمل مع عدد عائم مزدوج الدقة. |
| [Enum](./enum/) | يوفر طرقًا تُجرى بعض العمليات على قيم نوع التعداد. هذا نوع ثابت لا يقدم خدمات مثيل. يجب ألا تقوم بإنشاء مثيلات له بأي وسيلة. |
| [EnumGetNameHelper](./enumgetnamehelper/) | فئة مساعدة توفر وظيفة الحصول على الاسم النصي للثابت التعدادي. |
| [EnumParseHelper](./enumparsehelper/) | فئة مساعدة توفر وظيفة تحويل تمثيل نصي لثابت التعداد إلى قيمة التعداد المقابلة. |
| [Environment](./environment/) | خدمات [Environment](./environment/). هذا نوع ثابت لا يقدم خدمات مثيل. لا يجب إنشاء مثيلات له بأي وسيلة. |
| [HolderInitializer](./holderinitializer/) | تُستخدم هذه الفئة للحصول على مرجع دائم إلى مثيل الكائن، سواء كان قيمة يسارية أو يمينية. للحصول على مثل هذا المرجع، استخدم طريقة 'HoldIfTemporary' التي لديها ثلاثة تحميلات. اثنتان منهما تأخذان rvalue كمعامل وتُعيدان المرجع إليه. الثالثة، على النقيض، تأخذ lvalue كمعامل، تُنشئ نسخة من المؤشر، ثم تُعيد المرجع لتلك النسخة. كما أن الفئة تحتوي على طريقة 'Hold' لاحتفاظ بالقيمة الممررة دون شرط (تُستخدم لنسخ قيم المتغيرات المحلية على المكدس أو مراجعها الفرعية). |
| [HolderInitializer< T, false >](./holderinitializer_tmpl_t__false__end_tmpl/) | تخصيص [HolderInitializer](./holderinitializer/) للحالة التي يكون فيها T نوع قيمة. سياق الاستخدام يسمح بإرجاع مرجع إلى كائنات مؤقتة، حيث يُضمن أن المُستدعي سيُنسخ المثيل. لذا يُستخدم هذا التخصيص كقالب ولا يفعل شيئًا. |
| [IsBoxable](./isboxable/) | شرط قالب يتحقق ما إذا كان تعبئة النوع المحدد مدعومة. |
| [IsExceptionWrapper](./isexceptionwrapper/) | شرط قالب يحدد ما إذا كان النوع المحدد فئة استثناء أو أحد فروعها. |
| [IsNullable](./isnullable/) | شرط قالب يحدد ما إذا كان معامل القالب T في [Nullable](./nullable/) أو أحد فروعه. |
| [IsSmartPtr](./issmartptr/) | فئة صفة للتحقق ما إذا كان النوع تخصيصًا لفئة [SmartPtr](./smartptr/). |
| [IsStringByteSequence](./isstringbytesequence/) | سحر القالب للتحقق ما إذا كان النوع سلسلة من أحرف النص. |
| [IsStringLiteral](./isstringliteral/) | سحر القالب للتحقق ما إذا كان النوع حرفًا ثابتًا (string literal). |
| [IsStringPointer](./isstringpointer/) | سحر القالب للتحقق ما إذا كان النوع مؤشرًا إلى سلسلة حروف. |
| [IsWeakPtr](./isweakptr/) | فئة صفات للتحقق ما إذا كانت فئة معينة تخصيصًا لفئة [System::WeakPtr](./weakptr/). لا تتحقق ما إذا كان المثيل فعليًا في الوضع الضعيف. |
| [MakeConstRef](./makeconstref/) | صفة لتجعل النوع العام "مرجع ثابت" إذا كان [String](./string/) أو نوع SmartPtr<>. |
| [Math](./math/) | يحتوي على دوال رياضية. هذا نوع ثابت لا يقدم خدمات مثيل. يجب ألا تنشئ له مثيلات بأي وسيلة. |
| [MathF](./mathf/) | يحتوي على دوال رياضية للقيم العائمة ذات الدقة الأحادية. هذا نوع ثابت لا يقدم خدمات مثيل. يجب ألا تنشئ له مثيلات بأي وسيلة. |
| [MethodArgumentTuple< R(*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | يعرّف tuple لتخزين معطيات الدالة. |
| [MethodArgumentTuple< R(C::*)(Args...) const >](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/) | يعرّف tuple لتخزين معطيات الدالة. |
| [MethodArgumentTuple< R(C::*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | يعرّف tuple لتخزين معطيات الدالة. |
| [MulticastDelegateTypeInfo](./multicastdelegatetypeinfo/) | يمثل مؤشرًا إلى كائن [TypeInfo](./typeinfo/) يحتوي على معلومات حول فئة MulticastDelegate. |
| [RemoveShared](./removeshared/) | هياكل صفة لإزالة SharedPtr/WeakPtr من نوع المتغيّر. |
| [SByte](./sbyte/) | يحتوي على طرق للعمل مع عدد صحيح 8-بت. |
| [ScopeGuard](./scopeguard/) | فئة الخدمة التي توفر خدمات لتشغيل كائن دالة معين عندما يخرج مثيل الفئة من النطاق. |
| [Single](./single/) | يحتوي على طرق للعمل مع عدد عائم ذو دقة أحادية. |
| [TestCompare](./testcompare/) | بنية خدمة توفر واجهة لمقارنة المجموعات. |
| [TestTools](./testtools/) | يوفر مجموعة من الطرق المفيدة التي تتحقق من بعض الخصائص الأساسية للأنواع المختلفة والدوال. |
| [TestToolsExt](./testtoolsext/) | دوال شائعة للاستخدام في اختبار الترجمة. |
| [TypeInfoPtr](./typeinfoptr/) | غلاف لمؤشر إلى مثيل فئة [TypeInfo](./typeinfo/). يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](./smartptr/) لإدارة كائنات هذا النوع. |
| [UInt16](./uint16/) | يحتوي على طرق للعمل مع عدد صحيح غير موقع 16-بت. |
| [UInt32](./uint32/) | يحتوي على طرق للعمل مع عدد صحيح غير موقع 32-بت. |
| [UInt64](./uint64/) | يحتوي على طرق للعمل مع عدد صحيح غير موقع 64-بت. |
| [ValueTupleTypeInfo](./valuetupletypeinfo/) | يمثل مؤشرًا إلى كائن [TypeInfo](./typeinfo/) يحتوي على معلومات حول فئة [ValueTuple](./valuetuple/). |
| [WeakPtrFromTypeParameter](./weakptrfromtypeparameter/) | هيكل صفة لتحويل نوع المتغيّر إلى مؤشر ضعيف، إذا كان نوع مؤشر. |

## Functions

| الدالة | الوصف |
| --- | --- |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(std::initializer_list\<T\>) | دالة مصنع تنشئ كائن [Array](./array/) جديد، وتملأه بالعناصر من قائمة التهيئة المحددة وتُعيد مؤشرًا ذكيًا يشير إلى كائن [Array](./array/). |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(Args\&&...) | دالة مصنع تنشئ كائن [Array](./array/) جديد وتمرّر الوسائط المحددة إلى مُنشئه. |
| std::enable_if\<std::is_integral\<Integral\>::value, [ArrayPtr](./arrayptr/)\<T\>\>::type [MakeArray](./makearray/)(Integral, Args\&&...) | دالة مصنع تقوم بإنشاء كائن [Array](./array/) جديد بتمرير الوسائط المحددة إلى مُنشئه. |
| **bool** [operator==](./operator_equal_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) | |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | يحدد ما إذا كان كائن [Nullable](./nullable/) المحدد يمثل قيمة تساوي null. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | يحدد ما إذا كانت القيمة المحددة مساوية للقيمة التي يمثلها كائن [Nullable](./nullable/) المحدد عن طريق تطبيق [operator==()](./operator_equal_equal/) على هاتين القيمتين. |
| **bool** [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | يقارن مساواة مؤشرين ذكيين. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | يتحقق مما إذا كان المؤشر الذكي null. |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | مقارنة مساواة بين مؤشر ذكي ومؤشر بسيط (C). |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | مقارنة مساواة بين مؤشر ذكي ومؤشر بسيط (C). |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(T const\&, std::nullptr_t) | يتحقق مما إذا كان كائن نوع القيمة (هيكل C# مترجم، إلخ) هو null. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(std::nullptr_t, T const\&) | يتحقق مما إذا كان كائن نوع القيمة (هيكل C# مترجم، إلخ) هو null. |
| **bool** [operator==](./operator_equal_equal/)(Chars\&, const [String](./string/)\&) | مقارنة [String](./string/). |
| **bool** [operator==](./operator_equal_equal/)(T\&, const [String](./string/)\&) | مقارنة [String](./string/). |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | مقارنة [Object](./object/) وسلسلة. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [String](./string/)\&) | يتحقق مما إذا كانت السلسلة null. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | يحدد ما إذا كانت عناوين URI التي يمثلها الكائن الحالي والكائن المحدد متساوية. |
| **bool** [operator!=](./operator_not_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) | |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | يحدد ما إذا كان كائن [Nullable](./nullable/) المحدد يمثل قيمة لا تساوي null. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | يحدد ما إذا كانت القيمة المحددة غير مساوية للقيمة التي يمثلها كائن [Nullable](./nullable/) المحدد عن طريق تطبيق [operator!=()](./operator_not_equal/) على هاتين القيمتين. |
| **bool** [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | يقارن عدم مساواة مؤشرين ذكيين. |
| **bool** [operator!=](./operator_not_equal/)([SmartPtr](./smartptr/)\<X\> const\&, std::nullptr_t) | يتحقق مما إذا كان المؤشر الذكي ليس null. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | يتحقق مما إذا كان المؤشر الذكي ليس null. |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | مقارنة عدم مساواة بين مؤشر ذكي ومؤشر بسيط (C). |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | مقارنة مساواة بين مؤشر ذكي ومؤشر بسيط (C). |
| **bool** [operator!=](./operator_not_equal/)(Chars\&, const [String](./string/)\&) | مقارنة [String](./string/). |
| **bool** [operator!=](./operator_not_equal/)(T\&, const [String](./string/)\&) | مقارنة [String](./string/). |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | مقارنة [Object](./object/) وسلسلة. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [String](./string/)\&) | يتحقق مما إذا كانت السلسلة null. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | يحدد ما إذا كانت عناوين URI التي يمثلها الكائن الحالي والكائن المحدد غير متساوية. |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) | |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) | |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) | |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) | |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator<](./operator_less/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | دائمًا ما تُعيد false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | يحدد ما إذا كانت القيمة المحددة أصغر من القيمة التي يمثلها كائن [Nullable](./nullable/) المحدد عن طريق تطبيق [operator<()](./operator_less/) على هاتين القيمتين. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | دائمًا ما تُعيد false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | يحدد ما إذا كانت القيمة المحددة أصغر أو مساوية للقيمة التي يمثلها كائن [Nullable](./nullable/) المحدد عن طريق تطبيق [operator<=()](./operator_less_equal/) على هاتين القيمتين. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator>](./operator_greater/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | دائمًا ما تُعيد false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | يحدد ما إذا كانت القيمة المحددة أكبر من القيمة التي يمثلها كائن [Nullable](./nullable/) المحدد عن طريق تطبيق [operator>()](./operator_greater/) على هاتين القيمتين. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | دائمًا ما تُعيد false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | يحدد ما إذا كانت القيمة المحددة أكبر أو مساوية للقيمة التي يمثلها كائن [Nullable](./nullable/) المحدد عن طريق تطبيق [operator>=()](./operator_greater_equal/) على هاتين القيمتين. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| void [PrintTo](./printto/)([DateTime](./datetime/), std::ostream *) | يطبع القيمة إلى ostream. يُستخدم غالبًا للتصحيح. |
| void [PrintTo](./printto/)([DateTimeOffset](./datetimeoffset/), std::ostream *) | يطبع القيمة إلى ostream. يُستخدم غالبًا للتصحيح. |
| void [PrintTo](./printto/)(const [Decimal](./decimal/)\&, ::std::ostream *) | يكتب القيمة التي يمثلها الكائن المحدد إلى تدفق الإخراج المحدد. |
| void [PrintTo](./printto/)(const [Details_Exception](./details_exception/)\&, std::ostream *) | يطبع القيمة إلى ostream. يُستخدم غالبًا للتصحيح. |
| void [PrintTo](./printto/)(const [ExceptionWrapper](./exceptionwrapper/)\<T\>\&, std::ostream *) | يطبع القيمة إلى ostream. يُستخدم غالبًا للتصحيح. |
| void [PrintTo](./printto/)(const [Guid](./guid/)\&, std::ostream *) | يطبع القيمة إلى ostream. يُستخدم غالبًا للتصحيح. |
| void [PrintTo](./printto/)(const [Nullable](./nullable/)\<T\>\&, std::ostream *) | يطبع القيمة إلى ostream. يُستخدم غالبًا للتصحيح. |
| void [PrintTo](./printto/)(const [System::Object](./object/)\&, std::ostream *) | يطبع القيمة إلى ostream. يُستخدم غالبًا للتصحيح. |
| std::enable_if_t\<detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | يطبع القيمة إلى ostream. يُستخدم غالبًا للتصحيح. |
| std::enable_if_t<\!detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | يطبع القيمة إلى ostream. يُستخدم غالبًا للتصحيح. |
| void [PrintTo](./printto/)(const [System::String](./string/)\&, std::ostream *) | يطبع السلسلة إلى ostream. يُستخدم غالبًا للتصحيح. |
| void [PrintTo](./printto/)([TimeSpan](./timespan/), std::ostream *) | يطبع القيمة إلى ostream. يُستخدم غالبًا للتصحيح. |
| void [PrintTo](./printto/)(const [WeakPtr](./weakptr/)\<T\>\&, std::ostream *) | يطبع القيمة إلى ostream. يُستخدم غالبًا للتصحيح. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTime](./datetime/)) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTime](./datetime/)) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTimeOffset](./datetimeoffset/)) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTimeOffset](./datetimeoffset/)) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Decimal](./decimal/)\&) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Decimal](./decimal/)\&) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Exception](./exception/)\&) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Exception](./exception/)\&) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Guid](./guid/)\&) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Guid](./guid/)\&) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Nullable](./nullable/)\<T\>\&) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Nullable](./nullable/)\<T\>\&) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [System::Object](./object/)\&) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [System::Object](./object/)\&) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [OperatingSystem](./operatingsystem/)\&) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [OperatingSystem](./operatingsystem/)\&) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [String](./string/)\&) | يخرج سلسلة إلى تدفق الإخراج باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [String](./string/)\&) | يخرج سلسلة إلى تدفق الإخراج. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [TimeSpan](./timespan/)) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [TimeSpan](./timespan/)) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [TypeInfo](./typeinfo/)\&) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [TypeInfo](./typeinfo/)\&) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Version](./version/)\&) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Version](./version/)\&) | يدخل البيانات إلى الدفق. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | يدخل البيانات إلى الدفق باستخدام ترميز UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | يدخل البيانات إلى الدفق. |
| auto [operator-](./operator_minus/)([DayOfWeek](./dayofweek/), [DayOfWeek](./dayofweek/)) | تحسب عدد الأيام بين يومين من أيام الأسبوع. |
| [Decimal](./decimal/) [operator-](./operator_minus/)(const T\&, const [Decimal](./decimal/)\&) | تعيد نسخة جديدة من الفئة [Decimal](./decimal/) التي تمثل قيمة هي نتيجة طرح القيمة التي يمثلها كائن [Decimal](./decimal/) المحدد من القيمة المحددة. |
| MulticastDelegate\<T\> [operator-](./operator_minus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | يفصل جميع ردود النداء في المفوضية اليمنى عن نهاية قائمة ردود النداء في المفوضية اليسرى. |
| auto [operator-](./operator_minus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | يطرح القيم غير القابلة للـ null والقابلة للـ null. |
| [Decimal](./decimal/) [operator+](./operator_plus/)(const T\&, const [Decimal](./decimal/)\&) | يرجع مثيلًا جديدًا من الفئة [Decimal](./decimal/) التي تمثل قيمة هي مجموع القيمة المحددة والقيمة التي يمثلها الكائن [Decimal](./decimal/) المحدد. |
| MulticastDelegate\<T\> [operator+](./operator_plus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | يوّصل جميع ردود النداء من المفوضية اليمنى إلى نهاية قائمة ردود النداء للمفوضية اليسرى. |
| auto [operator+](./operator_plus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | يجمع القيم غير القابلة للـ null والقابلة للـ null. |
| std::enable_if\<[IsStringLiteral](./isstringliteral/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) دمج. |
| std::enable_if\<[IsStringPointer](./isstringpointer/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) دمج. |
| [String](./string/) [operator+](./operator_plus/)(const char_t, const [String](./string/)\&) | [String](./string/) دمج. |
| [Decimal](./decimal/) [operator*](./operator_star/)(const T\&, const [Decimal](./decimal/)\&) | يرجع مثيلًا جديدًا من الفئة [Decimal](./decimal/) التي تمثل قيمة هي نتيجة ضرب القيمة المحددة والقيمة التي يمثلها الكائن [Decimal](./decimal/) المحدد. |
| [Decimal](./decimal/) [operator/](./operator_div/)(const T\&, const [Decimal](./decimal/)\&) | يرجع مثيلًا جديدًا من الفئة [Decimal](./decimal/) التي تمثل قيمة هي نتيجة قسمة القيمة المحددة والقيمة التي يمثلها الكائن [Decimal](./decimal/) المحدد. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | يرجع المرجع إلى النسخة المفردة المُنشأة افتراضيًا من نوع الاستثناء. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | يرجع المرجع إلى النسخة المفردة المُنشأة افتراضيًا من النوع غير الاستثنائي. |
| T\& [Discard](./discard/)(T\&&) | يرجع النسخة المؤقتة المُنشأة افتراضيًا من النوع المحدد، والتي يمكن وضعها بدلاً من إهمال المتغيّر '_' . |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [BuildObject](./buildobject/)(Args\&&...) | إنشاء كائن بملكية مشتركة. |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [InitObject](./initobject/)(const [SharedPtr](./sharedptr/)\<T\>\&) | يبدأ تهيئة كائن بملكية مشتركة. |
| Details::ObjectBuilder\<Details::ArrayStorage\<T\>\> [BuildArray](./buildarray/)() | إنشاء مصفوفة. |
| Details::ObjectBuilder\<T\> [Build](./build/)(Args\&&...) | إنشاء كائن بملكية مباشرة. |
| **bool** [Is](./is/)(const ExpressionT\&, ResultT\&) | ينفّذ ترجمة نمط إعلان 'is'. |
| std::enable_if_t<\!std::is_base_of\<Details::Pattern, ConstantT\>::value, **bool**\> [Is](./is/)(const ExpressionT\&, const ConstantT\&) | ينفّذ ترجمة نمط ثابت 'is'. |
| std::enable_if_t\<std::is_base_of\<Details::Pattern, A\>::value, **bool**\> [Is](./is/)(const E\&, const A\&) | دالة مطابقة على المستوى الأعلى. تُطبّق نمطًا على قيمة. |
| static **bool** [IsNull](./isnull/)(const T\&) | ينفّذ نمط 'is null'. |
| **bool** [Less](./less/)(const ExpressionT\&, const ConstantT\&) | ينفّذ ترجمة نمط النسبي '<'. |
| **bool** [Greater](./greater/)(const ExpressionT\&, const ConstantT\&) | ينفّذ ترجمة نمط النسبي '>'. |
| **bool** [LEqual](./lequal/)(const ExpressionT\&, const ConstantT\&) | ينفّذ ترجمة نمط النسبي '<=' . |
| **bool** [GEqual](./gequal/)(const ExpressionT\&, const ConstantT\&) | ينفّذ ترجمة نمط النسبي '>=' . |
| **bool** [Set](./set/)(ExpressionT\&, const ExpressionT\&) | ينفّذ ترجمة نمط 'var'. |
| **bool** [IsTuple](./istuple/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, **int32_t**) | يتحقق مما إذا كان الكائن عبارة عن Tuple (يُطبق واجهة ITuple). يُستخدم في تنفيذ نمط موضعي. |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&) | دالة للحصول على العنصر N من الـ Tuple المُعطى. تحميل زائدة للكيان الأساسي. |
| auto [Get](./get/)(const T\&) | دالة للحصول على العنصر N من الـ Tuple المُعطى. تحميل زائدة للأجسام التي لها طريقة Deconstruct. |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<T\>\&) | دالة للحصول على العنصر N من الـ Tuple المُعطى. تحميل زائدة للمؤشرات المشتركة. |
| auto\& [Get](./get/)(T\&, const [Index](./index/)\&) | تنفيذ لتعبيرات collection[index]. |
| auto [Get](./get/)(T\&, const [Range](./range/)\&) | يرجع شريحة من المجموعة المحددة معرفة بالنطاق المُعطى. |
| auto [Get](./get/)(const [ValueTuple](./valuetuple/)\<Args...\>\&) | يحصل على العنصر N من Tuple القيم. |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<T\>\> [MakeYieldEnumerable](./makeyieldenumerable/)(const Details::YieldFunction\<T\>\&) | ينشئ IEnumerable من دالة yield. |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerator](../system.collections.generic/ienumerator/)\<T\>\> [MakeYieldEnumerator](./makeyieldenumerator/)(const Details::YieldFunction\<T\>\&) | ينشئ IEnumerator من دالة yield. |
| std::enable_if_t\<Details::is_lambda_void_void\<T\>::value\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | الدالة الوحيدة التي تحاكي سلوك عبارة try[-catch]-finally في C#. أثناء ترجمة عبارة try[-catch]-finally في C# مع تمكين خيار المترجم finally_statement_as_lambda وتعيينه إلى true، تُترجم العبارة إلى استدعاء هذه الدالة. |
| std::enable_if_t\<Details::is_lambda_void_boolref\<T\>::value, **bool**\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | الدالة الوحيدة التي تحاكي سلوك عبارة try[-catch]-finally في C#. أثناء ترجمة عبارة try[-catch]-finally في C# مع تمكين خيار المترجم finally_statement_as_lambda وتعيينه إلى true، تُترجم العبارة إلى استدعاء هذه الدالة. يتعامل هذا التحميل الزائد مع الحالة التي تكون فيها قيمة إرجاع كائن الدالة الذي يُطبق جزء try[-catch] من عبارة try[-catch]-finally هي bool. |
| std::enable_if_t\<Details::is_lambda_nonovoid_boolref\<T\>::value, std::optional\<Details::ResultOf\<T, **bool**\&\>\>\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | الدالة الوحيدة التي تحاكي سلوك عبارة try[-catch]-finally في C#. أثناء ترجمة عبارة try[-catch]-finally في C# مع تمكين خيار المترجم finally_statement_as_lambda وتعيينه إلى true، تُترجم العبارة إلى استدعاء هذه الدالة. يتعامل هذا التحميل الزائد مع الحالة التي تكون فيها قيمة إرجاع كائن الدالة الذي يُطبق جزء try[-catch] من عبارة try[-catch]-finally هي bool&. |
| [DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>::Reference [Ref](./ref/)([DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\&) | ينشئ مرجعًا لكائن [DynamicWeakPtr](./dynamicweakptr/). يُستخدم بواسطة المترجم عند تمرير معلمات الدالة بالمرجع. |
| T\& [Ref](./ref/)(T\&) | دالة مساعدة للحصول على مراجع للكائنات. تُستخدم لضمان أن [System::DynamicWeakPtr](./dynamicweakptr/) يُحدّث الكائن المرجعي بعد التعيينات. |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | هذه الخاصية الدالية تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامه مع حلقة for القائمة على النطاق. هذا التحميل الزائد لـ Enumerable بدون أساليب begin()، end() مع معامل نوع الهدف للعبارة (auto& value : IterateOver<SomeType>(enumerable)). |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | هذه الخاصية الدالية تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامه مع حلقة for القائمة على النطاق. هذا التحميل الزائد لـ Enumerable بدون أساليب begin()، end() مع معامل نوع الهدف الافتراضي للعبارة (auto& value : IterateOver(enumerable)) تمثيلًا للكود C# التالي foreach (var value in enumerable). |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | هذه الخاصية الدالية تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامه مع حلقة for القائمة على النطاق. هذا التحميل الزائد لـ Enumerable مع أساليب begin()، end() مع معامل نوع الهدف الافتراضي للعبارة (auto& value : IterateOver(enumerable)). |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | هذه الخاصية الدالية تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامه مع حلقة for القائمة على النطاق. هذا التحميل الزائد لـ Enumerable مع أساليب begin()، end() مع معامل نوع الهدف المطابق لنوع value_type الأصلي للمكرّر. |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&\!std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, Details::CppIteratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | هذه الخاصية الدالية تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامه مع حلقة for القائمة على النطاق. هذا التحميل الزائد لـ Enumerable مع أساليب begin()، end() مع نوع هدف مختلف ونوع value_type الأصلي للمكرّر. |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, Details::ValueTypeOfEnumerable\<Enumerable\>, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | هذه الخاصية الدالية تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامه مع حلقة for القائمة على النطاق. هذا التحميل الزائد لـ Enumerable هذا مع نوع الهدف الافتراضي. |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | هذه الخاصية الدالية تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامه مع حلقة for القائمة على النطاق. هذا التحميل الزائد لـ Enumerable بدون أساليب begin()، end() مع معامل نوع الهدف للعبارة (auto& value : IterateOver<SomeType>(enumerable)). |
| std::enable_if\<std::is_scalar\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | يرجع كود تجزئة للقيمة السلمية المحددة. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&[System::IsSmartPtr](./issmartptr/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | يرجع كود تجزئة للكائن المحدد. |
| std::enable_if\<[System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | يرجع كود تجزئة للكائن المحدد الذي هو استثناء. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\![System::IsSmartPtr](./issmartptr/)\<T\>::value\&&\![System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | يرجع كود تجزئة للكائن المحدد الذي ليس مؤشرًا ذكيًا ولا استثناءً. |
| int [GetHashCode](./gethashcode/)(const std::thread::id\&) | تخصيص لـ std::thread::id؛ يرجع كود التجزئة للكائن Thread المحدد. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast_noexcept](./cast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | يُجري تحويلًا على كائنات [SmartPtr](./smartptr/). |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast](./cast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | يُجري تحويلًا على كائنات [SmartPtr](./smartptr/). |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)(const TFrom\&) | عمليات تحويل قديمة مهجورة. سيتم إزالتها في الإصدارات المستقبلية. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | يُجري تحويلًا ديناميكيًا على كائنات [SmartPtr](./smartptr/). |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | يُجري تحويلًا ديناميكيًا على الكائنات إلى كائنات استثناء. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast](./dynamiccast/)(const TFrom\&) | يُجري تحويلًا ديناميكيًا على كائنات الاستثناء. |
| std::enable_if<\!std::is_enum\<TTo\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | يُجري تحويلًا ديناميكيًا على كائنات [SmartPtr](./smartptr/). |
| std::enable_if\<std::is_enum\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | يفك تغليف enum المعبأ عبر التحويل. |
| [CastResult](./castresult/)\<TTo\>::type [DynamicCast](./dynamiccast/)(std::nullptr_t) | يُجري تحويلًا ديناميكيًا للكائنات الفارغة (null). |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&std::is_convertible\<TTo, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom\&) | يُجري تحويلًا ديناميكيًا على الكائنات غير المؤشرية. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | ينفذ تحويلًا ديناميكيًا على الكائنات إلى كائنات استثناء. |
| std::enable_if\<std::is_pointer\<TTo\>::value\&&std::is_same\<IntPtr, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom) | ينفذ تحويلًا ديناميكيًا من IntPtr إلى مؤشر. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | ينفذ تحويلًا ثابتًا على كائنات [SmartPtr](./smartptr/). |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | ينفذ تحويلًا ثابتًا على كائنات [WeakPtr](./weakptr/). |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)(const TFrom\&) | ينفذ تحويلًا ثابتًا على كائنات استثناء. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | ينفذ تحويلًا ثابتًا على الكائنات إلى كائنات استثناء. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | ينفذ تحويلًا ثابتًا على كائنات [SmartPtr](./smartptr/). |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | ينفذ تحويلًا ثابتًا على كائنات [WeakPtr](./weakptr/). |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)(std::nullptr_t) | ينفذ تحويلًا ثابتًا للكائنات الفارغة. |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(TFrom) | تخصص لأنواع حسابية. |
| std::enable_if\<std::is_same\<TTo, [System::String](./string/)\>::value, TTo\>::type [StaticCast](./staticcast/)(TTo) | معالجة التحويل من [String](./string/) إلى [String](./string/). |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom *) | تخصص لأنواع حسابية. |
| std::enable_if<\!std::is_same\<TFrom, [System::String](./string/)\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&\!std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | ينفذ تحويلًا ثابتًا على كائنات غير المؤشر. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | ينفذ تحويلًا ثابتًا على كائنات استثناء. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\>) | ينفذ تحويلًا ثابتًا على الكائنات إلى كائنات استثناء. |
| [CastResult](./castresult/)\<TTo\>::type [ConstCast](./constcast/)(const [SmartPtr](./smartptr/)\<TFrom\>\&) | نهاية التحويلات المهملة. |
| [CastResult](./castresult/)\<TTo\>::type [ForceStaticCast](./forcestaticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | ينفذ تحويلًا ثابتًا حقيقيًا على كائنات [SmartPtr](./smartptr/). |
| [SmartPtr](./smartptr/)\<[Object](./object/)\> [MemberwiseClone](./memberwiseclone/)(T *) | ينفذ استنساخًا عضوًا بعضًا باستخدام منشئ النسخ. |
| [SharedPtr](./sharedptr/)\<T\> [With](./with/)(const [SharedPtr](./sharedptr/)\<T\>\&, const A\&) | ينشئ نسخة من سجل المرجع ويطبق الدالة المبدئة عليه. |
| T [With](./with/)(const T\&, const A\&) | ينسخ سجل البنية ويطبق الدالة المبدئة عليه. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم عندما يكون نوع المصدر ونوع النتيجة متطابقين. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم عندما يكون تحويل على شكل مُنشئ بسيط مطلوبًا. |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لأغلفة الاستثناء. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لتحويل الكائن إلى استثناء. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم عندما يكون كل من المصدر والنتيجة مؤشرات ذكية (دون SmartPtr<...> صريح في نوع النتيجة). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::RawPointer, typename [CastResult](./castresult/)\<std::remove_pointer_t\<Result\>\>::type\> [ExplicitCast](./explicitcast/)(Source) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم عند تحويل مؤشر خام إلى مؤشر ذكي. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم عندما يكون كل من المصدر والنتيجة مؤشرات ذكية (مع SmartPtr<...> صريح في نوع النتيجة). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لإلغاء تغليف كائن إلى نوع قابل للاختفاء. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لتغليف قيمة قابلة للاختفاء. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لإلغاء تغليف كائن قابل للاختفاء. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::EnumBoxing, [SmartPtr](./smartptr/)\<[BoxedValueBase](./boxedvaluebase/)\>\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لتغليف تعداد. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::HeapifyBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لنسخ أنواع القيم إلى الكومة عندما يجب الإشارة إلى نوع القيمة كمؤشر ذكي (في الأنماط العامة المقيدة بنوع الواجهة ولكن المتخصصة بالهيكل الذي يطبق هذه الواجهة). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم للحصول على الواجهات من أنواع القيم. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لتغليف شائع. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::StringBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لتغليف [System::String](./string/). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لإلغاء تغليف الواجهات. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Unboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لإلغاء تغليف شائع. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم لتحويل nullptr. |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل صريح. يستخدم للتحويل بين المصفوفات. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم عندما يكون تحويل على شكل مُنشئ بسيط مطلوبًا. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم عندما يكون نوع المصدر ونوع النتيجة متطابقين. |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم لأغلفة الاستثناء. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم لتحويل الكائن إلى استثناء. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم عندما يكون كل من المصدر والنتيجة مؤشرات ذكية. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم عندما يكون كل من المصدر والنتيجة مؤشرات ذكية (مع SmartPtr<...> صريح في نوع النتيجة). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم لإلغاء تغليف كائن إلى قيمة قابلة للاختفاء. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. إلغاء تغليف غير صالح إلى نوع غير كائن. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InvalidUnboxing, Result\> [AsCast](./ascast/)(const Source\&) | إلغاء تغليف غير صالح إلى نوع غير كائن. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم لتغليف كائن قابل للاختفاء. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم لتغليف كائن شائع. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم لتغليف كائن شائع. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToString, Result\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم لإلغاء تغليف السلسلة. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم لتصنيف nullptr. |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | يحوّل نوع المصدر إلى نوع النتيجة باستخدام تحويل عبر عامل 'as'. يستخدم للتحويل بين المصفوفات. |
| static auto [SafeInvoke](./safeinvoke/)(T0\&&, T1\&&) | تنفيذ ترجمة عامل '?.'. |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::String >](./objecttype_dcolon_gettype_less_system_dcolon_string__greater/)() | ينفّذ ترجمة typeof(). التحميل الزائد لـ [String](./string/). |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::DateTime >](./objecttype_dcolon_gettype_less_system_dcolon_datetime__greater/)() | ينفّذ ترجمة typeof(). التحميل الزائد لـ [DateTime](./datetime/). |
| **bool** [Equals](./equals/)(const TA\&, const TB\&) | يحدد مساواة قيمتين بتطبيق [operator==()](./operator_equal_equal/) عليهما. |
| **bool** [Equals< float, float >](./equals_less_float,_float__greater/)(const **float**\&, const **float**\&) | تخصص لقيم الفاصلة العائمة ذات الدقة المفردة. على الرغم من أن قيم NaN ذات الفاصلة العائمة تُعرّف وفقًا لـ IEC 60559:1989 بأنها تُقارن دائمًا على أنها غير متساوية، فإن العقدة لـ [System.Object.Equals](./object/equals/) تتطلب أن الالتفافات يجب أن تفي بمتطلبات عامل التكافؤ. لذلك، تُعيد System.Double.Equals و System.Single.Equals القيمة True عند مقارنة قيمتين NaN، بينما يُعيد عامل المساواة القيمة False في تلك الحالة، كما هو مطلوب وفقًا للمعيار. |
| **bool** [Equals< double, double >](./equals_less_double,_double__greater/)(const **double**\&, const **double**\&) | تخصص لقيم الفاصلة العائمة ذات الدقة المزدوجة. |
| std::enable_if_t<\!std::is_floating_point\<TA\>::value\&&\!std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | يقارن قيمتين. |
| std::enable_if_t\<std::is_floating_point\<TA\>::value\&&std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | يقارن قيمتين عائمتين. |
| **bool** [IsNaN](./isnan/)(const T\&) | يحدد ما إذا كانت القيمة المحددة هي قيمة غير رقمية (NaN). |
| **bool** [IsInfinity](./isinfinity/)(const T\&) | يحدد ما إذا كانت القيمة المحددة تمثل اللانهاية. |
| **bool** [IsPositiveInfinity](./ispositiveinfinity/)(const T\&) | يحدد ما إذا كانت القيمة المحددة تمثل اللانهاية الموجبة. |
| **bool** [IsNegativeInfinity](./isnegativeinfinity/)(const T\&) | يحدد ما إذا كانت القيمة المحددة تمثل اللانهاية السالبة. |
| TTo [CheckedCast](./checkedcast/)(TFrom) | يحدد ما إذا كانت القيمة المحددة تقع ضمن نطاق قيم النوع **TTo** وإذا كان الأمر كذلك يقوم بالتحويل إلى النوع **TTo**. |
| [ScopeGuard](./scopeguard/)\<F\> [MakeScopeGuard](./makescopeguard/)(F) | دالة مصنع تنشئ كائنات من الفئة ScopedGuard. |
| T [setter_wrap](./setter_wrap/)(void(*)(T2), T) | إصدار بديل لدوال الضابط الثابت مع تحويل النوع. |
| std::enable_if\<std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_wrap](./setter_wrap/)(Host *const, void(HostSet::*)(T2), T) | إصدار بديل لدوال الضابط للنسخة مع تحويل النوع. |
| T [setter_increment_wrap](./setter_increment_wrap/)(T(*)(), void(*)(T)) | المترجم يترجم تعبيرات الزيادة في C# التي تستهدف خاصية الفئة التي لديها ضابط وجالب معرفين، إلى استدعاء هذه الدالة. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_increment_wrap](./setter_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | المترجم يترجم تعبيرات الزيادة في C# التي تستهدف خاصية الفئة التي لديها ضابط وجالب معرفين، إلى استدعاء هذه الدالة. |
| T [setter_post_increment_wrap](./setter_post_increment_wrap/)(T(*)(), void(*)(T)) | المترجم يترجم تعبيرات الزيادة في C# التي تستهدف خاصية الفئة التي لديها ضابط وجالب معرفين، إلى استدعاء هذه الدالة. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | المترجم يترجم تعبيرات الزيادة في C# التي تستهدف خاصية الكائن التي لديها ضابط وجالب معرفين، إلى استدعاء هذه الدالة (إصدار بديل للجالب غير الثابت). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | المترجم يترجم تعبيرات الزيادة في C# التي تستهدف خاصية الكائن التي لديها ضابط وجالب معرفين، إلى استدعاء هذه الدالة (إصدار بديل للجالب الثابت). |
| T [setter_decrement_wrap](./setter_decrement_wrap/)(T(*)(), void(*)(T)) | المترجم يترجم تعبيرات النقصان المسبق في C# التي تستهدف خاصية الفئة التي لديها ضابط وجالب معرفين، إلى استدعاء هذه الدالة. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | المترجم يترجم تعبيرات النقصان المسبق في C# التي تستهدف خاصية الكائن التي لديها ضابط وجالب معرفين، إلى استدعاء هذه الدالة (إصدار بديل للجالب غير الثابت). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | المترجم يترجم تعبيرات النقصان المسبق في C# التي تستهدف خاصية الكائن التي لديها ضابط وجالب معرفين، إلى استدعاء هذه الدالة (إصدار بديل للجالب الثابت). |
| T [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(T(*)(), void(*)(T)) | المترجم يترجم تعبيرات النقصان ما بعد في C# التي تستهدف خاصية الفئة التي لديها ضابط وجالب معرفين، إلى استدعاء هذه الدالة. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | المترجم يترجم تعبيرات النقصان ما بعد في C# التي تستهدف خاصية الكائن التي لديها ضابط وجالب معرفين، إلى استدعاء هذه الدالة (إصدار بديل للجالب غير الثابت). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | المترجم يترجم تعبيرات النقصان ما بعد في C# التي تستهدف خاصية الكائن التي لديها ضابط وجالب معرفين، إلى استدعاء هذه الدالة (إصدار بديل للجالب الثابت). |
| std::enable_if<\![IsSmartPtr](./issmartptr/)\<T\>::value, [SmartPtr](./smartptr/)\<T\>\>::type [MakeObject](./makeobject/)(Args\&&...) | ينشئ كائنًا على الـ heap ويعيد مؤشرًا مشتركًا إليه. |
| std::enable_if\<[IsSmartPtr](./issmartptr/)\<T\>::value, T\>::type [MakeObject](./makeobject/)(Args\&&...) | ينشئ كائنًا على الـ heap ويعيد مؤشرًا مشتركًا إليه. |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(X *) | يحول المؤشر الخام إلى مؤشر ذكي. |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(const X *) | يحول المؤشر الخام إلى مؤشر ذكي. إصدار بديل للمؤشرات الثابتة. مفيد على سبيل المثال عند استخدام المتغيّر `this` في طرق C# التي تم ترجمتها كـ const. |
| [SmartPtr](./smartptr/)\<Y\> [static_pointer_cast](./static_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | يحول المؤشرات الذكية باستخدام static_cast. |
| [SmartPtr](./smartptr/)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | يحول المؤشرات الذكية باستخدام dynamic_cast. |
| [SmartPtr](./smartptr/)\<Y\> [const_pointer_cast](./const_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | يحول المؤشرات الذكية باستخدام const_cast. |
| T * [get_pointer](./get_pointer/)([System::SmartPtr](./smartptr/)\<T\> const\&) | يحصل على الكائن المرجعي للمؤشر الذكي. |
| std::enable_if<\!System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | يؤدي إلى التحويل الصريح لعناصر الكائن القابل للتعداد المحدد إلى نوع مختلف. |
| std::enable_if\<System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | يؤدي إلى التحويل الصريح لعناصر الكائن القابل للتعداد المحدد إلى نوع مختلف. |
| std::enable_if_t\<[System::IsSmartPtr](./issmartptr/)\<From\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | يؤدي إلى تحويل عناصر المصفوفة المحددة إلى نوع مختلف. تجاوز للحالات التي يكون فيها From كائن [SmartPtr](./smartptr/). |
| std::enable_if_t<\![System::IsSmartPtr](./issmartptr/)\<From\>::value\&&[System::IsBoxable](./isboxable/)\<From\>::value\&&std::is_same\<To, [System::SharedPtr](./sharedptr/)\<[Object](./object/)\>\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | يؤدي إلى تحويل عناصر المصفوفة المحددة إلى نوع مختلف. تجاوز للحالات التي يكون فيها From قابلًا للـ Boxable و To هو [Object](./object/)[]. |
| [SharedPtr](./sharedptr/)\<[Array](./array/)\<To\>\> [DynamicCastArray](./dynamiccastarray/)(const [SharedPtr](./sharedptr/)\<[Array](./array/)\<From\>\>\&) | يؤدي إلى تحويل عناصر المصفوفة المحددة إلى نوع مختلف. |
| std::istream\& [operator>>](./operator_greater_greater/)(std::istream\&, [String](./string/)\&) | يحصل على سلسلة نصية من تدفق الإدخال باستخدام ترميز UTF-8. |
| std::wistream\& [operator>>](./operator_greater_greater/)(std::wistream\&, [String](./string/)\&) | يحصل على سلسلة نصية من تدفق الإدخال. |
| [TaskPtr](./taskptr/) [MakeAsync](./makeasync/)(const Details::AsyncFunction\&) |  |
| [RTaskPtr](./rtaskptr/)\<T\> [MakeAsync](./makeasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ResultValueTask](../system.threading.tasks/resultvaluetask/)\<T\> [MakeValueAsync](./makevalueasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ValueTask](../system.threading.tasks/valuetask/) [MakeValueAsync](./makevalueasync/)(const Details::AsyncFunction\&) |  |
| [ValueTuple](./valuetuple/)\<Args...\> [MakeTuple](./maketuple/)(Args...) | ينشئ مجموعة (tuple) على المكدس. |
| [ValueTuple](./valuetuple/)\<Args...\> [TieTuple](./tietuple/)(Args\&&...) | ينشئ مجموعة (tuple) مرتبطة ببعض القيم. |
| **bool** [is_vp_test](./is_vp_test/)(const ::testing::TestInfo *) |  |
| **bool** [is_parametrized_test](./is_parametrized_test/)(const ::testing::TestInfo *) |  |
| std::string [ForEachMemberGVName](./foreachmembergvname/)() |  |

## التعدادات

| التعداد | الوصف |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | تعداد يحتوي على قيم تمثل صيغًا مختلفة للبيانات المشفرة بصيغة base-64. |
| [DateTimeKind](./datetimekind/) | قيم التعداد التي تمثل أنواع التاريخ والوقت. |
| [DayOfWeek](./dayofweek/) | تعداد يمثل يوماً من أيام الأسبوع. |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | يحدد موقع المتغير البيئي. |
| [MidpointRounding](./midpointrounding/) | يحدد سلوك دوال التقريب. |
| [PlatformID](./platformid/) | يمثل منصة نظام تشغيل. |
| [SmartPtrMode](./smartptrmode/) | نوع المؤشر [SmartPtr](./smartptr/): ضعيف أو مشترك. يحدد ما إذا كان المؤشر يُحصى عندما يُقرر ما إذا كان يجب حذف الكائن أم لا. |
| [StringSplitOptions](./stringsplitoptions/) | يحدد سلوك تقسيم السلسلة. |
| [StringComparison](./stringcomparison/) | يعرف نمط مقارنة السلاسل. |
| [TypeCode](./typecode/) | يمثل نوع كائن. |
| [UriKind](./urikind/) | يمثل أنواع عناوين URI. |
| [UriComponents](./uricomponents/) | يمثل مكونات URI. |
| [UriFormat](./uriformat/) | يحدد كيفية هروب URI. |
| [UriHostNameType](./urihostnametype/) | يمثل نوع اسم المضيف. |
| [UriPartial](./uripartial/) | يمثل أجزاء URI لطريقة [Uri.GetLeftPart](./uri/getleftpart/). |

## تعريفات الأنواع

| التعريف | الوصف |
| --- | --- |
| [IFormatProviderPtr](./iformatproviderptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::IFormatProvider](./iformatprovider/). |
| [DecoderFallbackPtr](./decoderfallbackptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Text::DecoderFallback](../system.text/decoderfallback/). |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/). |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/). |
| [EncoderFallbackPtr](./encoderfallbackptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Text::EncoderFallback](../system.text/encoderfallback/). |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/). |
| [EncoderPtr](./encoderptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Text::Encoder](../system.text/encoder/). |
| [DecoderPtr](./decoderptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Text::Decoder](../system.text/decoder/). |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/). |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/). |
| [EncodingPtr](./encodingptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Text::Encoding](../system.text/encoding/). |
| [EncodingInfoPtr](./encodinginfoptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Text::EncodingInfo](../system.text/encodinginfo/). |
| [StreamPtr](./streamptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::IO::Stream](../system.io/stream/). |
| [FileStreamPtr](./filestreamptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::IO::FileStream](../system.io/filestream/). |
| [MemoryStreamPtr](./memorystreamptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::IO::MemoryStream](../system.io/memorystream/). |
| [StreamReaderPtr](./streamreaderptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::IO::StreamReader](../system.io/streamreader/). |
| [StreamWriterPtr](./streamwriterptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::IO::StreamWriter](../system.io/streamwriter/). |
| [FileInfoPtr](./fileinfoptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::IO::FileInfo](../system.io/fileinfo/). |
| [FileSystemInfoPtr](./filesysteminfoptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::IO::FileSystemInfo](../system.io/filesysteminfo/). |
| [DirectoryInfoPtr](./directoryinfoptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::IO::DirectoryInfo](../system.io/directoryinfo/). |
| [TaskPtr](./taskptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Threading::Tasks::Task](../system.threading.tasks/task/). |
| [RTaskPtr](./rtaskptr/) | اسم مستعار لمؤشر ذكي يشير إلى نسخة من الفئة [System::Threading::Tasks::ResultTask](../system.threading.tasks/resulttask/). |
| [FunctionPtr](./functionptr/) | اسم مستعار لنوع دالة مع استدعاء افتراضي. |
| [Action](./action/) | نوع موزّع يشير إلى طرق لا تُعيد قيمة. |
| [AggregateException](./aggregateexception/) |  |
| [ByteArrayPtr](./bytearrayptr/) | اسم مستعار لكائن مؤشر ذكي يشير إلى مصفوفة من الأعداد الصحيحة غير الموقعة ذات 8 بت. |
| [AsyncCallback](./asynccallback/) | نوع موزّع يمثل طريقة تُستدعى عند اكتمال العملية غير المتزامنة. |
| [BadImageFormatException](./badimageformatexception/) | الإستثناء الذي يُرمى عندما تكون صورة ملف مكتبة ربط ديناميكي (DLL) أو برنامج قابل للتنفيذ غير صالحة. لا تقم أبدًا بلف كائنات BadImageFormatException داخل [System::SmartPtr](./smartptr/). |
| [Converter](./converter/) | يمثل مؤشرًا إلى الكيان القابل للاستدعاء الذي يقبل وسيطًا واحدًا من النوع **TInput** ويرجع قيمة من النوع **TOutput**. |
| [Event](./event/) | يمثل حدثًا - آلية يتم من خلالها إبلاغ المشتركين بحدوث شيء ما عن طريق استدعاء موزّع. |
| [EventArgsPtr](./eventargsptr/) | مؤشر مشترك إلى نسخة من الفئة [EventArgs](./eventargs/). |
| [EventHandler](./eventhandler/) | يمثل طريقة تتفاعل مع حدث وتعالجّه. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبدًا الفئة [System::SmartPtr](./smartptr/) لإدارة كائنات من هذا النوع. |
| [ExceptionPtr](./exceptionptr/) | اسم مستعار للنوع يُستخدم بواسطة أغلفة الاستثناءات. |
| [Exception](./exception/) | اسم مستعار يُستعمل بدلًا من Details::Exception. |
| [SystemException](./systemexception/) |  |
| [ApplicationException](./applicationexception/) |  |
| [InvalidOperationException](./invalidoperationexception/) |  |
| [InvalidProgramException](./invalidprogramexception/) |  |
| [InvalidTimeZoneException](./invalidtimezoneexception/) |  |
| [TimeZoneNotFoundException](./timezonenotfoundexception/) |  |
| [ObjectDisposedException](./objectdisposedexception/) |  |
| [NotImplementedException](./notimplementedexception/) |  |
| [NotSupportedException](./notsupportedexception/) |  |
| [PlatformNotSupportedException](./platformnotsupportedexception/) |  |
| [ArgumentException](./argumentexception/) |  |
| [ArgumentNullException](./argumentnullexception/) |  |
| [ArgumentOutOfRangeException](./argumentoutofrangeexception/) |  |
| [FormatException](./formatexception/) |  |
| [UriFormatException](./uriformatexception/) |  |
| [ArithmeticException](./arithmeticexception/) |  |
| [OverflowException](./overflowexception/) |  |
| [DivideByZeroException](./dividebyzeroexception/) |  |
| [OutOfMemoryException](./outofmemoryexception/) |  |
| [IndexOutOfRangeException](./indexoutofrangeexception/) |  |
| [RankException](./rankexception/) |  |
| [InvalidCastException](./invalidcastexception/) |  |
| [NullReferenceException](./nullreferenceexception/) |  |
| [UnauthorizedAccessException](./unauthorizedaccessexception/) |  |
| [MemberAccessException](./memberaccessexception/) |  |
| [MethodAccessException](./methodaccessexception/) |  |
| [OperationCanceledException](./operationcanceledexception/) |  |
| [StackOverflowException](./stackoverflowexception/) |  |
| [TimeoutException](./timeoutexception/) |  |
| [ExecutionEngineException](./executionengineexception/) |  |
| [TypeInitializationException](./typeinitializationexception/) |  |
| [DataMisalignedException](./datamisalignedexception/) |  |
| [IAsyncResultPtr](./iasyncresultptr/) | مؤشرات مشتركة إلى [IAsyncResult](./iasyncresult/). |
| [MakeConstRef_t](./makeconstref_t/) | نوع مساعد لـ [MakeConstRef](./makeconstref/) المعدل. |
| [Predicate](./predicate/) | يمثل مؤشرًا إلى دالة شرطية - كيانًا قابلًا للاستدعاء يقبل معاملًا واحدًا ويُرجِع قيمة منطقية. |
| [ArrayPtr](./arrayptr/) | اسم مستعار لنوع 'مؤشر إلى مصفوفة'. |
| [SharedPtr](./sharedptr/) | اسم مستعار لمؤشر ذكي يُستخدم على نطاق واسع في المكتبة. |
| [StringComparerPtr](./stringcomparerptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من الفئة [StringComparer](./stringcomparer/). |
| [TimeZonePtr](./timezoneptr/) | مؤشر مشترك إلى نسخة من الفئة [TimeZone](./timezone/). |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من الفئة [TimeZoneInfo](./timezoneinfo/). |