---
title: Path
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: पाथ को संशोधित करने के लिए विधियों को प्रदान करता है। यह कोई इंस्टेंस सेवाएँ न रखने वाला स्थिर प्रकार है। इसे किसी भी माध्यम से कभी भी इंस्टेंस नहीं बनाना चाहिए।
type: docs
weight: 339
url: /hi/system.io/path/
---
## Path क्लास

Provides methods for manipulating paths. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Path
```

## मेथड्स

| Method | Description |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट फ़ाइल पथ में एक्सटेंशन बदलता है। |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | निर्दिष्ट पथ में अमान्य अक्षर हैं या नहीं जाँचकर यह निर्धारित करता है कि पथ वैध है या नहीं। यदि पथ में अमान्य अक्षर होते हैं तो एक अपवाद उत्पन्न किया जाता है। |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | निर्दिष्ट पथ खंडों को एकल पथ में मिलाता है, आवश्यक होने पर खंडों के बीच डायरेक्टरी सेपरेटर अक्षर डालता है। |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट दो पथ खंडों को एकल पथ में मिलाता है, आवश्यक होने पर खंडों के बीच डायरेक्टरी सेपरेटर अक्षर डालता है। |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट तीन पथ खंडों को एकल पथ में मिलाता है, आवश्यक होने पर खंडों के बीच डायरेक्टरी सेपरेटर अक्षर डालता है। |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट चार पथ खंडों को एकल पथ में मिलाता है, आवश्यक होने पर खंडों के बीच डायरेक्टरी सेपरेटर अक्षर डालता है। |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ द्वारा संदर्भित डायरेक्टरी का नाम लौटाता है। |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ द्वारा संदर्भित फ़ाइल का एक्सटेंशन लौटाता है। |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ द्वारा संदर्भित फ़ाइल का नाम लौटाता है। |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ द्वारा संदर्भित फ़ाइल का एक्सटेंशन के बिना नाम लौटाता है। |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ को पूर्ण (एब्सोल्यूट) पथ में परिवर्तित करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | फ़ाइल नामों में अनुमति नहीं वाले अक्षरों को सम्मिलित करने वाला एक एरे लौटाता है। |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | पथ नामों में अनुमति नहीं वाले अक्षरों को सम्मिलित करने वाला एक एरे लौटाता है। |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ की रूट डायरेक्टरी लौटाता है। |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | एक यादृच्छिक रूप से उत्पन्न फ़ाइल नाम लौटाता है। |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | एक अद्वितीय नाम वाली नई फ़ाइल बनाता है और उसका पूर्ण पथ लौटाता है। |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | एक अद्वितीय नाम वाली नई फ़ाइल बनाता है और उसका पूर्ण पथ लौटाता है। Is a synonym of [GetTempFileName_()](./gettempfilename_/) method. |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | वर्तमान उपयोगकर्ता की अस्थायी डायरेक्टरी का पथ लौटाता है। |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ किसी फ़ाइल को एक्सटेंशन के साथ संदर्भित करता है या नहीं निर्धारित करता है। |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | निर्धारित करता है कि निर्दिष्ट पथ में रूट मौजूद है या नहीं। |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ को सामान्यीकृत करता है। |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | निर्दिष्ट पथ का प्रतिनिधित्व करने वाला boost::filesystem::path क्लास का एक इंस्टेंस लौटाता है। |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | निर्दिष्ट Boost पथ ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## फ़ील्ड्स

| Field | Description |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | पथ में डायरेक्टरी स्तरों को अलग करने के लिए प्रयुक्त वैकल्पिक अक्षर। |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | पथ में डायरेक्टरी स्तरों को अलग करने के लिए प्रयुक्त अक्षर। |
| static [PathSeparator](./pathseparator/) | पर्यावरण वेरिएबल्स में पथ स्ट्रिंग्स को अलग करने के लिए प्रयुक्त सेपरेटर अक्षर। |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | वॉल्यूम सेपरेटर अक्षर। |
## टिप्पणी



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // एक यादृच्छिक फ़ाइलनाम उत्पन्न करता है।
  auto filename = Path::GetRandomFileName();

  // फ़ाइलनाम के बारे में जानकारी प्रिंट करता है।
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## देखें

* नेमस्पेस [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)