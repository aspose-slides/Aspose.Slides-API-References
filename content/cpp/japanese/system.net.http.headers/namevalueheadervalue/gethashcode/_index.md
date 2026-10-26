---
title: GetHashCode()
second_title: Aspose.Slides for C++ API リファレンス
description: C# の Object.GetHashCode() メソッドに相当します。カスタムオブジェクトのハッシュ化を可能にします。
type: docs
weight: 53
url: /ja/system.net.http.headers/namevalueheadervalue/gethashcode/
---
## NameValueHeaderValue::GetHashCode() const メソッド

C# の [Object.GetHashCode()](../../../system/object/gethashcode/) メソッドに相当します。カスタムオブジェクトのハッシュ化を可能にします。

```cpp
int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode() const override
```

### 戻り値

対応するクラスで計算されたハッシュコードの値。

## NameValueHeaderValue::GetHashCode(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) メソッド

コレクション内のすべての項目のハッシュコードを返します。

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue-class のインスタンスのコレクション。 |

### 戻り値

コレクション内のすべての項目のハッシュコード。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [NameValueHeaderValue](../)
* クラス [ObjectCollection](../../objectcollection/)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)