---
title: CheckPath()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट पथ में अवैध अक्षर हैं या नहीं, यह जांचकर यह निर्धारित करता है कि पथ वैध है या नहीं। यदि पथ में अवैध अक्षर होते हैं तो एक अपवाद फेंका जाता है।
type: docs
weight: 209
url: /hi/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) मेथड

निर्दिष्ट पथ में अवैध अक्षर हैं या नहीं, यह जांचकर यह निर्धारित करता है कि पथ वैध है या नहीं। यदि पथ में अवैध अक्षर होते हैं तो एक अपवाद फेंका जाता है।

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | जाँचने के लिए पथ |
| msg | const [String](../../../system/string/)\& | अपवाद वस्तु के कंस्ट्रक्टर को पास करने वाला संदेश |
| allow_empty | **bool** | निर्दिष्ट करता है कि एक खाली या null स्ट्रिंग को सही पथ (true) माना जाना चाहिए या नहीं (false); यदि यह पैरामीटर false है और **path** खाली है तो ArgumentException फेंका जाता है; यदि यह पैरामीटर false है और **path** null है तो ArgumentNullException फेंका जाता है |

## See Also

* क्लास [String](../../../system/string/)
* क्लास [Path](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)