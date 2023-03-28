---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides for C++ API Reference
description: Set Macro hyperlink on a click.
type: docs
weight: 79
url: /cpp/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick([System::String](../../../system/string/)) method


Set Macro hyperlink on a click.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Name of the macro |

### Return Value

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Remarks



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHyperlink](../../ihyperlink/)
* Class [String](../../../system/string/)
* Class [IHyperlinkManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
