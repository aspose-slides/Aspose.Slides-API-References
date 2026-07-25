---
title: GetChildRows()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたリレーションを通じて子として扱われる行を取得します。
type: docs
weight: 27
url: /ja/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) メソッド

指定されたリレーションを通じて子として扱われる行を取得します。

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | 親行と子行の関係を指定するRelationオブジェクト。 |

### 戻り値

[Array](../../../system/array/) の子行が取得されました。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [DataRow](../)
* クラス [DataRelation](../../datarelation/)
* 名前空間 [System::Data](../../)
* ライブラリ [Aspose.Slides](../../../)