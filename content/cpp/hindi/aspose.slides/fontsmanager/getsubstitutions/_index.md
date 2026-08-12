---
title: GetSubstitutions()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति के रेंडरिंग के दौरान बदल दी जाने वाली फ़ॉन्ट्स के बारे में जानकारी प्राप्त करता है।
type: docs
weight: 66
url: /hi/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() विधि

प्रस्तुति के रेंडरिंग के दौरान बदल दी जाने वाली फ़ॉन्ट्स के बारे में जानकारी प्राप्त करता है।

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```

### रिटर्न वैल्यू

सभी फ़ॉन्ट प्रतिस्थापन की संग्रह [FontSubstitutionInfo](../../fontsubstitutioninfo/)।

## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) विधि

निर्दिष्ट स्लाइड्स के रेंडरिंग के दौरान बदल दी जाने वाले फ़ॉन्ट्स के बारे में जानकारी प्राप्त करता है।

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | फ़ॉन्ट प्रतिस्थापन जानकारी प्राप्त करने के लिए स्लाइड इंडेक्स की एक array, जो 1 से शुरू होती है। |

### रिटर्न वैल्यू

निर्दिष्ट स्लाइड्स के लिए सभी फ़ॉन्ट प्रतिस्थापन की एक संग्रह ([FontSubstitutionInfo](../../fontsubstitutioninfo/))।

## टिप्पणी

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [IEnumerable](../../../system.collections.generic/ienumerable/)
* क्लास [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* क्लास [FontsManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)