---
title: BindingFlags
second_title: Aspose.Slides for C++ API リファレンス
description: メンバーと型の検索モードおよびバインディングを定義します。
type: docs
weight: 157
url: /ja/system.reflection/bindingflags/
---
## BindingFlags 列挙体

メンバーと型の検索モードおよびバインディングを定義します。

```cpp
enum class BindingFlags
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Default | 0 | 特別なオプションはありません。 |
| IgnoreCase | 1 | アイテムを検索するときに名前の大文字小文字を無視します。 |
| DeclaredOnly | 2 | 型で宣言されたメンバーのみを検索し、基底型のメンバーは検索しません。 |
| Instance | 4 | インスタンス メンバーを検索します。 |
| Static | 8 | 静的メンバーを検索します。 |
| Public | 16 | パブリック メンバーを検索します。 |
| NonPublic | 32 | 非パブリック メンバーを検索します。 |
| FlattenHierarchy | 64 | 基底型のパブリックおよび保護された静的メンバーを検索します。 |
| InvokeMethod | 256 | メソッドを呼び出します。 |
| CreateInstance | 512 | リフレクトされた型のインスタンスを作成します。 |
| GetField | 1024 | フィールドの値を取得します。 |
| SetField | 2048 | フィールドの値を設定します。 |
| GetProperty | 4096 | プロパティの値を取得します。 |
| SetProperty | 8192 | プロパティの値を設定します。 |
| PutDispProperty | 16384 | COM プロパティを設定します。 |
| PutRefDispProperty | 32768 | COM 参照プロパティを設定します。 |
| ExactBinding | 65536 | 型バインディングは正確でなければならず、型の変更は許可されません。 |
| SuppressChangeType | 131072 | サポートされていません。 |
| OptionalParamBinding | 262144 | 引数の数に基づいてオーバーロードを選択します。 |
| IgnoreReturn | 16777216 | COM 相互運用の戻り値を無視します。 |

## 参照

* 名前空間 [System::Reflection](../)
* ライブラリ [Aspose.Slides](../../)