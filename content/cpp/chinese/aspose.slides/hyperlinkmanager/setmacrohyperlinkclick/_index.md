---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides C++ API 参考
description: 在点击时设置宏超链接。
type: docs
weight: 79
url: /zh/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) 方法

在点击时设置宏超链接。

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | 宏的名称 |

### 返回值

[Hyperlink](../../hyperlink/) 对象 [IHyperlink](../../ihyperlink/)

## 备注

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IHyperlink](../../ihyperlink/)
* 类 [String](../../../system/string/)
* 类 [HyperlinkManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)