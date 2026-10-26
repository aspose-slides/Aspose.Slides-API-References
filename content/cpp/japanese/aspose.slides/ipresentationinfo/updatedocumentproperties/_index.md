---
title: UpdateDocumentProperties()
second_title: Aspose.Slides for C++ API リファレンス
description: バインドされたプレゼンテーションのプロパティを更新します。
type: docs
weight: 92
url: /ja/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) メソッド

バインドされたプレゼンテーションのプロパティを更新します。

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | ドキュメント プロパティ [IDocumentProperties](../../idocumentproperties/) |
## 備考

このサンプルは、[IPresentationInfo::UpdateDocumentProperties](./) メソッドを呼び出して、[IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) メソッドの呼び出しで返されるドキュメントプロパティを更新する方法を示しています。 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IDocumentProperties](../../idocumentproperties/)
* クラス [IPresentationInfo](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)