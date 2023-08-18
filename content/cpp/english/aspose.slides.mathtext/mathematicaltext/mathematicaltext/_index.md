---
title: MathematicalText()
second_title: Aspose.Slides for C++ API Reference
description: "Default constructor (create String::Empty Value)"
type: docs
weight: 40
url: /aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() constructor


Default constructor (create String::Empty Value)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Remarks


Example: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) constructor


Create [MathText](../../) with single symbol

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char16_t | single symbol |
## Remarks



Example: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) constructor


Create [MathematicalText](../) from text

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | text value |
## Remarks



Example: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) constructor


Create [MathematicalText](../) from text and format settings

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | text value |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | text format settings |
## Remarks



Example: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MathematicalText](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)