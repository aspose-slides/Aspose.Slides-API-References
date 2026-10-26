---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides for C++ API リファレンス
description: 永続化に使用されるメソッドが PersistStream、PersistStreamInit、または PersistStorage のいずれかである場合の ActiveX コントロールの永続性を指定します。
type: docs
weight: 118
url: /ja/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() メソッド

永続化に使用されるメソッドが PersistStream、PersistStreamInit、または PersistStorage のいずれかである場合に、ActiveX コントロールの永続性を指定します。

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```
## 備考

次の例は、ActiveX のプロパティを変更するために ActiveXControlBinary プロパティを使用する方法を示しています：

```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // ActiveX プロパティをバイナリ ファイルに格納して管理する独自のメソッドを使用してください
    YourMethodHere(control->get_ActiveXControlBinary());
}
```
## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [Control](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)