---
title: GetSubstitutions()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेजेंटेशन के रेंडरिंग के दौरान बदल दिए जाने वाले फ़ॉन्ट्स के बारे में जानकारी प्राप्त करता है।
type: docs
weight: 66
url: /hi/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() method

प्रेजेंटेशन के रेंडरिंग के दौरान बदल दिए जाने वाले फ़ॉन्ट्स के बारे में जानकारी प्राप्त करता है।

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```

### रिटर्न वैल्यू

सभी फ़ॉन्ट प्रतिस्थापन का संग्रह [FontSubstitutionInfo](../../fontsubstitutioninfo/)।

## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) method

निर्दिष्ट स्लाइड्स के रेंडरिंग के दौरान बदल दिए जाने वाले फ़ॉन्ट्स के बारे में जानकारी प्राप्त करता है।

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | स्लाइड इंडेक्स की एक ऐरे, जिसके लिए फ़ॉन्ट प्रतिस्थापन जानकारी प्राप्त करनी है, 1 से शुरू। |

### रिटर्न वैल्यू

निर्दिष्ट स्लाइड्स के लिए सभी फ़ॉन्ट प्रतिस्थापन का संग्रह ([FontSubstitutionInfo](../../fontsubstitutioninfo/))।

## टिप्पणी

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [IEnumerable](../../../system.collections.generic/ienumerable/)
* क्लास [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* क्लास [IFontsManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)