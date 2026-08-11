---
title: Environment
second_title: مرجع API Aspose.Slides برای C++
description: خدمات Environment. این یک نوع ایستاتیک است که هیچ سرویس نمونه‌ای ندارد. شما نباید به هیچ وجه نمونه‌های آن را ایجاد کنید.
type: docs
weight: 1626
url: /fa/system/environment/
---
## Environment ساختار

[Environment](./) خدمات. این یک نوع ایستاتیک است که هیچ سرویس نمونه‌ای ندارد. شما نباید به هیچ وجه نمونه‌های آن را ایجاد کنید.

```cpp
class Environment
```

## متدها

| متد | توضیح |
| --- | --- |
| static void [Exit](./exit/)(int) | فرآیند جاری را خاتمه می‌دهد و کد خروجی مشخص‌شده را به سیستم‌عامل برمی‌گرداند. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | نام‌های متغیرهای محیطی یافت‌شده در رشتهٔ مشخص‌شده را با مقادیر آن متغیرها جایگزین می‌کند و رشتهٔ حاصل را برمی‌گرداند. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | فرآیند جاری را متوقف می‌کند. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | خط فرمان استفاده‌شده برای شروع فرآیند جاری را برمی‌گرداند. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | مسیر پوشهٔ کاری فعلی را برمی‌گرداند. |
| static int [get_ExitCode](./get_exitcode/)() | کد خروجی برای فرآیند جاری را برمی‌گرداند. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | بررسی می‌کند که آیا خاموش سازی در حال انجام است. اجرا نشده است. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | برای برنامه‌ها/کتابخانه‌های پلتفرم ۶۴-بیتی مقدار true برمی‌گرداند. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | نام NetBIOS این کامپیوتر را برمی‌گرداند. |
| static [String](../string/) [get_NewLine](./get_newline/)() | رشتهٔ newline تنظیم‌شده برای محیط فعلی را برمی‌گرداند. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | شی [OperatingSystem](../operatingsystem/) را برمی‌گرداند که شامل اطلاعات دربارهٔ سیستم‌عامل جاری است. |
| static int [get_ProcessorCount](./get_processorcount/)() | تعداد پردازنده‌های موجود در دستگاه جاری را برمی‌گرداند. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | رشته‌ای را برمی‌گرداند که شامل اطلاعات ردیابی پشتهٔ فعلی است. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | مسیر پوشهٔ سیستم را برمی‌گرداند. |
| static int [get_TickCount](./get_tickcount/)() | تعداد میلی‌ثانیه‌های گذشته از زمان شروع سیستم را برمی‌گرداند. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | نام دامنهٔ شبکهٔ کاربر فعلی را برمی‌گرداند. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | تعیین می‌کند که آیا فرآیند جاری در حالت کاربری تعاملی اجرا می‌شود. |
| static [String](../string/) [get_UserName](./get_username/)() | نام کاربری که در حال حاضر به سیستم‌عامل [Windows](../../system.windows/) وارد شده است را برمی‌گرداند. |
| static [Version](../version/) [get_Version](./get_version/)() | شی [Version](../version/) را برمی‌گرداند که اطلاعات دربارهٔ نسخهٔ زمان‌ اجرا مشترک را نشان می‌دهد. شمارهٔ نسخهٔ برگردانده‌شده توسط این متد صرفاً نمایشی است و به این معنی نیست که تمام کلاس‌های کتابخانه با آن نسخه سازگارند. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | مقدار حافظهٔ فیزیکی که به زمینهٔ فرآیند نگاشت شده است را برمی‌گرداند. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | آرایه‌ای شامل آرگومان‌های خط‌فرمان استفاده‌شده برای شروع فرآیند جاری را برمی‌گرداند. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | مقدار متغیر محیطی مشخص‌شده‌ای که با فرآیند جاری مرتبط است را برمی‌گرداند. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | مقدار متغیر محیطی مشخص‌شده از مکان مشخص‌شده را برمی‌گرداند. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | مقدار متغیر محیطی مشخص‌شده‌ای که با فرآیند جاری مرتبط است را برمی‌گرداند. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | یک دیکشنری شامل تمام نام‌های متغیرهای محیطی و مقادیرشان که با فرآیند جاری مرتبط هستند را برمی‌گرداند. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | یک دیکشنری شامل تمام نام‌های متغیرهای محیطی و مقادیرشان از مکان مشخص‌شده را برمی‌گرداند. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | مقدار متغیر محیطی مشخص‌شده‌ای که با فرآیند جاری مرتبط است را برمی‌گرداند. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | مسیر کامل به پوشهٔ سیستم مشخص‌شده را برمی‌گرداند. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | آرایه‌ای شامل نام تمام درایوهای منطقی در کامپیوتر جاری را برمی‌گرداند. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | تنها برای WSL مقدار true برمی‌گرداند. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | پوشهٔ مشخص‌شده را به عنوان پوشهٔ کاری فعلی تنظیم می‌کند. |
| static void [set_ExitCode](./set_exitcode/)(int) | مقدار مشخص‌شده را به عنوان کد خروجی برای فرآیند جاری تنظیم می‌کند. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | اجرا نشده است. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | اجرا نشده است. |

## Enums

| Enum | توضیح |
| --- | --- |
| [SpecialFolder](./specialfolder/) | نمایان‌گر پوشه‌های ویژهٔ سیستم است. |

## مراجع

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)