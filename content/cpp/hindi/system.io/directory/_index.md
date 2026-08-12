---
title: Directory
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: डायरेक्टरियों को बदलने के लिए विधियों को सम्मिलित करता है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं हैं। आपको कभी भी किसी भी माध्यम से इसके इंस्टेंस नहीं बनाना चाहिए।
type: docs
weight: 235
url: /hi/system.io/directory/
---
## डायरेक्टरी क्लास


डायरेक्टरीज़ को बदलने के लिए विधियों को सम्मिलित करता है। यह एक स्थैतिक प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं हैं। आपको कभी भी किसी भी माध्यम से इसके इंस्टेंस नहीं बनाना चाहिए।

```cpp
class Directory
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | यदि निर्दिष्ट पथ में डायरेक्टरियाँ मौजूद नहीं हैं तो सभी डायरेक्टरी बनाता है। |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | निर्दिष्ट फ़ाइल या डायरेक्टरी को हटाता है। यह कोई अपवाद नहीं उत्पन्न करता। |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | निर्दिष्ट खोज मानदंड को संतुष्ट करने वाली डायरेक्टरियों को खोजता है, या तो निर्दिष्ट डायरेक्टरी में या पूरी डायरेक्टरी ट्री में जो निर्दिष्ट डायरेक्टरी से शुरू होती है। |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | निर्दिष्ट खोज मानदंड को संतुष्ट करने वाली फ़ाइलों को खोजता है, या तो निर्दिष्ट डायरेक्टरी में या पूरी डायरेक्टरी ट्री में जो निर्दिष्ट डायरेक्टरी से शुरू होती है। |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | निर्धारित खोज मानदंड को संतुष्ट करने वाली फ़ाइलों और डायरेक्टरियों को खोजता है, या तो निर्दिष्ट डायरेक्टरी में या पूरी डायरेक्टरी ट्री में जो निर्दिष्ट डायरेक्टरी से शुरू होती है। |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | निर्धारित करता है कि क्या निर्धारित पथ मौजूदा डायरेक्टरी को दर्शाता है। |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का निर्माण समय स्थानीय समय के रूप में लौटाता है। |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का निर्माण समय UTC समय के रूप में लौटाता है। |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | वर्तमान डायरेक्टरी का पूर्ण नाम (पथ सहित) लौटाता है। |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | निर्दिष्ट खोज मानदंड को संतुष्ट करने वाली डायरेक्टरियों को खोजता है, या तो निर्दिष्ट डायरेक्टरी में या पूरी डायरेक्टरी ट्री में जो निर्दिष्ट डायरेक्टरी से शुरू होती है। |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ की मूल (रूट) डायरेक्टरी लौटाता है। |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | निर्दिष्ट खोज मानदंड को संतुष्ट करने वाली फ़ाइलों को खोजता है, या तो निर्दिष्ट डायरेक्टरी में या पूरी डायरेक्टरी ट्री में जो निर्दिष्ट डायरेक्टरी से शुरू होती है। |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | निर्धारित खोज मानदंड को संतुष्ट करने वाली फ़ाइलों और डायरेक्टरियों को खोजता है, या तो निर्दिष्ट डायरेक्टरी में या पूरी डायरेक्टरी ट्री में जो निर्दिष्ट डायरेक्टरी से शुरू होती है। |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का अंतिम एक्सेस समय स्थानीय समय के रूप में लौटाता है। |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का अंतिम एक्सेस समय UTC समय के रूप में लौटाता है। |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का अंतिम लिखने का समय स्थानीय समय के रूप में लौटाता है। |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का अंतिम लिखने का समय UTC समय के रूप में लौटाता है। |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | लागू नहीं किया गया। |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई की पैरेंट डायरेक्टरी का प्रतिनिधित्व करने वाले [DirectoryInfo](../directoryinfo/) ऑब्जेक्ट का एक साझा पॉइंटर लौटाता है। |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट इकाई को नई स्थिति में ले जाता है। यदि ले जाने वाली इकाई एक डायरेक्टरी है, तो यह अपनी सभी सामग्री के साथ ले जाई जाती है। |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | निर्दिष्ट इकाई का निर्माण समय स्थानीय समय के रूप में सेट करता है। |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | निर्दिष्ट इकाई का निर्माण समय UTC समय के रूप में सेट करता है। |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | वर्तमान डायरेक्टरी सेट करता है। |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | निर्दिष्ट इकाई का अंतिम एक्सेस समय स्थानीय समय के रूप में सेट करता है। |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | निर्दिष्ट इकाई का अंतिम एक्सेस समय UTC समय के रूप में सेट करता है। |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | निर्दिष्ट इकाई का अंतिम लिखने का समय स्थानीय समय के रूप में सेट करता है। |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | निर्दिष्ट इकाई का अंतिम लिखने का समय UTC समय के रूप में सेट करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | [String](../../system/string/) ऑब्जेक्ट्स के सेट पर क्रमिक करने वाले IEnumerable ऑब्जेक्ट के एक साझा पॉइंटर का उपनाम। |

## टिप्पणियाँ



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // डायरेक्टरियों के पथ वाली स्ट्रिंग्स बनाएं।
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // जाँचें कि डायरेक्टरियां मौजूद हैं या नहीं।
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // टेम्प डायरेक्टरी की जानकारी प्रिंट करें।
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
Directory 'C:\' मौजूद है।
Directory 'C:\Some directory' मौजूद नहीं है।
Directory 'C:\Users\lanor\AppData\Local\Temp\' मौजूद है।
निर्माण समय: 27.08.2021 14:21:42
अंतिम एक्सेस समय: 07.10.2021 12:16:41
अंतिम लिखने का समय: 07.10.2021 12:16:41
*/
```

## संबंधित देखें

* नेमस्पेस [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)