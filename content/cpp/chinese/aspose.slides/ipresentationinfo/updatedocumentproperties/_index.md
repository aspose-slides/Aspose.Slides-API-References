---
title: UpdateDocumentProperties()
second_title: Aspose.Slides C++ API 参考
description: 更新已绑定演示文稿的属性。
type: docs
weight: 92
url: /zh/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties>) 方法


更新已绑定的演示文稿的属性。

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)<[IDocumentProperties](../../idocumentproperties/)> | 文档属性 [IDocumentProperties](../../idocumentproperties/) |
## 备注



此示例演示了如何调用 [IPresentationInfo::UpdateDocumentProperties](./) 方法来更新由调用 [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) 方法返回的文档属性。 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDocumentProperties](../../idocumentproperties/)
* 类 [IPresentationInfo](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)