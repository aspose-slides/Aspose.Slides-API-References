---
title: Environment
second_title: Aspose.Slides for C++ API Referansı
description: Ortam hizmetleri. Bu bir örnek hizmeti olmayan statik bir türdür. Herhangi bir yolla onun örneklerini asla oluşturmayın.
type: docs
weight: 1626
url: /tr/system/environment/
---
## Environment yapısı


[Environment](./) services. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Environment
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static void [Exit](./exit/)(int) | Geçerli süreci sonlandırır ve belirtilen çıkış kodunu işletim sistemine döndürür. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Belirtilen dizede bulunan ortam değişkeni adlarını, bu değişkenlerin değerleriyle değiştirir ve ortaya çıkan dizeyi döndürür. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Geçerli süreci durdurur. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Geçerli süreci başlatmak için kullanılan komut satırını döndürür. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Geçerli çalışma dizininin yolunu döndürür. |
| static int [get_ExitCode](./get_exitcode/)() | Geçerli sürecin çıkış kodunu döndürür. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Kapatma işleminin devam edip etmediğini kontrol eder. NOT IMPLEMENTED. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | 64-bit platform yürütülebilir dosyalar/kütüphaneler için doğru (true) döndürür. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Bu bilgisayarın NetBIOS adını döndürür. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Geçerli ortam için ayarlanan satır sonu dizesini döndürür. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Geçerli işletim sistemi hakkında bilgi içeren [OperatingSystem](../operatingsystem/) nesnesini döndürür. |
| static int [get_ProcessorCount](./get_processorcount/)() | İşlemci sayısını ya da geçerli makinenin sayısını döndürür. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Geçerli yığın izleme bilgisini içeren dizeyi döndürür. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Sistem dizininin yolunu döndürür. |
| static int [get_TickCount](./get_tickcount/)() | Sisteminin başlatılmasından bu yana geçen milisaniye sayısını döndürür. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Geçerli kullanıcının ağ etki alanı adını döndürür. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Geçerli sürecin kullanıcı etkileşimli modda çalışıp çalışmadığını belirler. |
| static [String](../string/) [get_UserName](./get_username/)() | Şu anda [Windows](../../system.windows/) işletim sistemine giriş yapmış olan kullanıcının adını döndürür. |
| static [Version](../version/) [get_Version](./get_version/)() | Ortak dil çalışma zamanının sürümü hakkında bilgiyi temsil eden [Version](../version/) nesnesini döndürür. Bu yöntem tarafından döndürülen sürüm numarası aslında bir taklit olup, tüm kütüphane sınıflarının döndürülen sürüme göre davrandığı anlamına gelmez. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | İşlem bağlamına eşlenen fiziksel bellek miktarını döndürür. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Geçerli süreci başlatmak için kullanılan komut satırı argümanlarını içeren bir dizi döndürür. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Geçerli süreç ile ilişkili belirtilen ortam değişkeninin değerini döndürür. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Belirtilen konumdan belirtilen ortam değişkeninin değerini döndürür. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Geçerli süreç ile ilişkili belirtilen ortam değişkeninin değerini döndürür. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Geçerli süreç ile ilişkili tüm ortam değişkeni adlarını ve değerlerini içeren bir sözlük döndürür. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Belirtilen konumdan tüm ortam değişkeni adlarını ve değerlerini içeren bir sözlük döndürür. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Geçerli süreç ile ilişkili belirtilen ortam değişkeninin değerini döndürür. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Belirtilen sistem klasörünün tam nitelikli yolunu döndürür. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Geçerli bilgisayardaki tüm mantıksal sürücülerin adlarını içeren bir dizi döndürür. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Yalnızca WSL için doğru (true) döndürür. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Belirtilen dizini geçerli çalışma dizini olarak ayarlar. |
| static void [set_ExitCode](./set_exitcode/)(int) | Belirtilen değeri geçerli sürecin çıkış kodu olarak ayarlar. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NOT IMPLEMENTED. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NOT IMPLEMENTED. |

## Enum'lar

| Enum | Açıklama |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Sistem özel klasörlerini temsil eder. |

## Ayrıca Bakınız

* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)