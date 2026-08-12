---
title: Environment
second_title: Aspose.Slides for C++ API संदर्भ
description: पर्यावरण सेवाएँ। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं हैं। आपको इसे किसी भी माध्यम से इंस्टेंस नहीं बनाना चाहिए।
type: docs
weight: 1626
url: /hi/system/environment/
---
## पर्यावरण संरचना


[Environment](./) सेवाएँ। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं हैं। आपको इसे किसी भी तरीके से इंस्टेंस नहीं बनाना चाहिए।

```cpp
class Environment
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static void [Exit](./exit/)(int) | वर्तमान प्रक्रिया को समाप्त करता है और निर्दिष्ट बाहर निकलने कोड को ऑपरेटिंग सिस्टम को लौटाता है। |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग में पाए गए पर्यावरण चर के नामों को उनके मानों से बदलता है और परिणामी स्ट्रिंग लौटाता है। |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | वर्तमान प्रक्रिया को निरस्त करता है। |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | वर्तमान प्रक्रिया को शुरू करने के लिए उपयोग की गई कमांड लाइन लौटाता है। |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | वर्तमान कार्य निर्देशिका का पथ लौटाता है। |
| static int [get_ExitCode](./get_exitcode/)() | वर्तमान प्रक्रिया के लिए बाहर निकलने कोड लौटाता है। |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | जाँचता है कि शटडाउन प्रगति में है या नहीं। लागू नहीं किया गया है। |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | 64-बीट प्लेटफ़ॉर्म के निष्पादन योग्य/लाइब्रेरी के लिए true लौटाता है। |
| static [String](../string/) [get_MachineName](./get_machinename/)() | इस कंप्यूटर का NetBIOS नाम लौटाता है। |
| static [String](../string/) [get_NewLine](./get_newline/)() | वर्तमान पर्यावरण के लिए सेट किया गया नई पंक्ति स्ट्रिंग लौटाता है। |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | वर्तमान ऑपरेटिंग सिस्टम की जानकारी रखने वाले [OperatingSystem](../operatingsystem/) ऑब्जेक्ट को लौटाता है। |
| static int [get_ProcessorCount](./get_processorcount/)() | प्रोसेसरों या वर्तमान मशीन की संख्या लौटाता है। |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | वर्तमान स्टैक ट्रेस जानकारी रखने वाली स्ट्रिंग लौटाता है। |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | सिस्टम निर्देशिका का पथ लौटाता है। |
| static int [get_TickCount](./get_tickcount/)() | सिस्टम के शुरू होने के बाद से बीते मिलीसेकंड की संख्या लौटाता है। |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | वर्तमान उपयोगकर्ता का नेटवर्क डोमेन नाम लौटाता है। |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | निर्धारित करता है कि वर्तमान प्रक्रिया उपयोगकर्ता इंटरैक्टिव मोड में चल रही है या नहीं। |
| static [String](../string/) [get_UserName](./get_username/)() | वर्तमान में [Windows](../../system.windows/) OS में लॉग इन किए उपयोगकर्ता का नाम लौटाता है। |
| static [Version](../version/) [get_Version](./get_version/)() | वर्ज़न की जानकारी दर्शाने वाले [Version](../version/) ऑब्जेक्ट को लौटाता है। इस मेथड द्वारा लौटाया गया संस्करण नंबर केवल डमी है और इसका मतलब नहीं है कि सभी लाइब्रेरी क्लासेज़ लौटाए गए संस्करण के अनुसार कार्य करती हैं। |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | प्रोसेस संदर्भ में मैप की गई भौतिक मेमोरी की मात्रा लौटाता है। |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | वर्तमान प्रक्रिया को शुरू करने के लिए उपयोग किए गए कमांड-लाइन तर्कों को समाहित करने वाला एरे लौटाता है। |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | वर्तमान प्रक्रिया से संबंधित निर्दिष्ट पर्यावरण चर का मान लौटाता है। |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | निर्दिष्ट स्थान से निर्दिष्ट पर्यावरण चर का मान लौटाता है। |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | वर्तमान प्रक्रिया से संबंधित निर्दिष्ट पर्यावरण चर का मान लौटाता है। |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | वर्तमान प्रक्रिया से जुड़े सभी पर्यावरण चर के नाम और उनके मानों को समाहित करने वाला डिक्शनरी लौटाता है। |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | निर्दिष्ट स्थान से सभी पर्यावरण चर के नाम और उनके मानों को समाहित करने वाला डिक्शनरी लौटाता है। |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | वर्तमान प्रक्रिया से संबंधित निर्दिष्ट पर्यावरण चर का मान लौटाता है। |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | निर्दिष्ट सिस्टम फ़ोल्डर का पूर्ण योग्य पथ लौटाता है। |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | वर्तमान कंप्यूटर पर सभी लॉजिकल ड्राइव्स के नामों को समाहित करने वाला एरे लौटाता है। |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | केवल WSL के लिए true लौटाता है। |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | निर्दिष्ट निर्देशिका को वर्तमान कार्य निर्देशिका के रूप में सेट करता है। |
| static void [set_ExitCode](./set_exitcode/)(int) | निर्दिष्ट मान को वर्तमान प्रक्रिया के बाहर निकलने कोड के रूप में सेट करता है। |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | लागू नहीं किया गया। |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | लागू नहीं किया गया। |

## एनम

| एनम | विवरण |
| --- | --- |
| [SpecialFolder](./specialfolder/) | सिस्टम विशेष फ़ोल्डरों का प्रतिनिधित्व करता है। |

## देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)