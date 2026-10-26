---
title: Environment
second_title: Aspose.Slides لـ C++ مرجع API
description: خدمات البيئة. هذا نوع ثابت ولا يحتوي على خدمات مثيل. يجب أبدًا عدم إنشاء نسخ منه بأي وسيلة.
type: docs
weight: 1626
url: /ar/system/environment/
---
## Environment بنية

[Environment](./) خدمات. هذا نوع ثابت لا يحتوي على خدمات مثيل. يجب أبدًا عدم إنشاء نسخ منه بأي وسيلة.

```cpp
class Environment
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static void [Exit](./exit/)(int) | ينهي العملية الحالية ويعيد رمز الخروج المحدد إلى نظام التشغيل. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | يستبدل أسماء المتغيرات البيئية الموجودة في السلسلة المحددة بقيم تلك المتغيرات ويعيد السلسلة الناتجة. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | يوقف العملية الحالية. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | يُعيد سطر الأوامر المستخدم لبدء العملية الحالية. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | يُعيد المسار إلى دليل العمل الحالي. |
| static int [get_ExitCode](./get_exitcode/)() | يُعيد رمز الخروج للعملية الحالية. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | يتحقق مما إذا كان الإغلاق جارٍ. غير مُنفذ. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | يعيد true للملفات التنفيذية/المكتبات على منصة 64-bit. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | يُعيد اسم NetBIOS لهذا الحاسب. |
| static [String](../string/) [get_NewLine](./get_newline/)() | يُعيد سلسلة سطر جديد المضبوطة للبيئة الحالية. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | يُعيد كائن [OperatingSystem](../operatingsystem/) الذي يحتوي على معلومات حول نظام التشغيل الحالي. |
| static int [get_ProcessorCount](./get_processorcount/)() | يُعيد عدد المعالجات في الجهاز الحالي. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | يُعيد السلسلة التي تحتوي على معلومات تتبع المكدس الحالي. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | يُعيد المسار إلى دليل النظام. |
| static int [get_TickCount](./get_tickcount/)() | يُعيد عدد الملليثواني التي مرت منذ بدء تشغيل النظام. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | يُعيد اسم مجال الشبكة للمستخدم الحالي. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | يحدد ما إذا كانت العملية الحالية تعمل في وضع التفاعل مع المستخدم. |
| static [String](../string/) [get_UserName](./get_username/)() | يُعيد اسم المستخدم المسجل حالياً في نظام التشغيل [Windows](../../system.windows/). |
| static [Version](../version/) [get_Version](./get_version/)() | يُعيد كائن [Version](../version/) الذي يمثل معلومات عن نسخة runtime للغة المشتركة. رقم النسخة الذي يُعيده هذا الأسلوب هو مجرد قيمة تجريبية ولا يعني أن جميع فئات المكتبة تتصرف وفقاً للنسخة المعادة. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | يُعيد مقدار الذاكرة الفعلية المربوطة بسياق العملية. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | يُعيد مصفوفة تحتوي على معطيات سطر الأوامر المستخدمة لبدء العملية الحالية. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | يُعيد قيمة المتغير البيئي المحدد المرتبط بالعملية الحالية. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | يُعيد قيمة المتغير البيئي المحدد من الموقع المحدد. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | يُعيد قيمة المتغير البيئي المحدد المرتبط بالعملية الحالية. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | يُعيد قاموساً يحتوي على جميع أسماء المتغيرات البيئية وقيمها المرتبطة بالعملية الحالية. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | يُعيد قاموساً يحتوي على جميع أسماء المتغيرات البيئية وقيمها من الموقع المحدد. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | يُعيد قيمة المتغير البيئي المحدد المرتبط بالعملية الحالية. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | يُعيد مساراً كاملاً إلى المجلد النظام المحدد. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | يُعيد مصفوفة تحتوي على أسماء جميع الأقراص المنطقية على الحاسوب الحالي. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | يعيد true فقط لـ WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | يضبط الدليل المحدد كدليل العمل الحالي. |
| static void [set_ExitCode](./set_exitcode/)(int) | يضبط القيمة المحددة كرمز خروج للعملية الحالية. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | غير مُنفذ. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | غير مُنفذ. |

## التعدادات

| التعداد | الوصف |
| --- | --- |
| [SpecialFolder](./specialfolder/) | يمثل المجلدات الخاصة بالنظام. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)