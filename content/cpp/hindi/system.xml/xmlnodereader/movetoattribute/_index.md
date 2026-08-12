---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट नाम वाले विशेषता पर जाता है।
type: docs
weight: 300
url: /hi/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) विधि

निर्दिष्ट नाम वाले विशेषता पर जाता है।

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | विशेषता का योग्य नाम। |

### रिटर्न मान

**true** यदि विशेषता मिली; अन्यथा **false**। यदि **false**, तो रीडर की स्थिति नहीं बदलती।

## XmlNodeReader::MoveToAttribute(String, String) विधि

निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले विशेषता पर जाता है।

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | विशेषता का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | विशेषता का नेमस्पेस URI। |

### रिटर्न मान

**true** यदि विशेषता मिली; अन्यथा **false**। यदि **false**, तो रीडर की स्थिति नहीं बदलती।

## XmlNodeReader::MoveToAttribute(int32_t) विधि

निर्दिष्ट अनुक्रमांक वाले विशेषता पर जाता है।

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| attributeIndex | **int32_t** | विशेषता का अनुक्रमांक। |

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNodeReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)