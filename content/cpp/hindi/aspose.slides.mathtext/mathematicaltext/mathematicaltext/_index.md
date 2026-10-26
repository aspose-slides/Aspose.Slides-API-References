---
title: MathematicalText()
second_title: "Aspose.Slides for C++ API संदर्भ"
description: "डिफ़ॉल्ट कंस्ट्रक्टर (String::Empty मान बनाएँ)"
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() कंस्ट्रक्टर

डिफ़ॉल्ट कंस्ट्रक्टर (String::Empty मान बनाएँ)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## टिप्पणी

उदाहरण: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) कंस्ट्रक्टर

एकल प्रतीक के साथ [MathText](../../) बनाएँ

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathSymbol | char16_t | एकल प्रतीक |
## टिप्पणी

उदाहरण: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) कंस्ट्रक्टर

पाठ से [MathematicalText](../) बनाएँ

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | पाठ मान |
## टिप्पणी

उदाहरण: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) कंस्ट्रक्टर

पाठ और स्वरूप सेटिंग्स से [MathematicalText](../) बनाएँ

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | पाठ मान |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | पाठ स्वरूप सेटिंग्स |
## टिप्पणी

उदाहरण: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [MathematicalText](../)
* क्लास [String](../../../system/string/)
* क्लास [IPortionFormat](../../../aspose.slides/iportionformat/)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)