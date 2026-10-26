---
title: get_Persistence()
second_title: Aspose.Slides for C++ API リファレンス
description: ActiveX コントロールのプロパティを保存するために使用されるメソッドを取得します。読み取り専用 PersistenceType。
type: docs
weight: 1
url: /ja/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() メソッド

ActiveX コントロールのプロパティを保存するために使用されるメソッドを取得します。 読み取り専用 [PersistenceType](../../persistencetype/)。

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## 備考

次の例は、Persistence プロパティを使用して、ActiveX オブジェクトのプロパティが XML ベースの ActiveX プロパティとして変更可能かどうかを確認する方法を示しています: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // ActiveX プロパティがバイナリ ファイルに保存されている管理のために独自のメソッドを使用してください
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## 参照

* 列挙型 [PersistenceType](../../persistencetype/)
* クラス [Control](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)