---
title: FieldAttributes
second_title: Aspose.Slides for C++ API リファレンス
description: 反映されたフィールド属性。
type: docs
weight: 170
url: /ja/system.reflection/fieldattributes/
---
## FieldAttributes 列挙体

反映されたフィールド属性。

```cpp
enum class FieldAttributes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| FieldAccessMask | 7 | メンバーアクセスマスク。 このマスクを使用してアクセシビリティ情報を取得します。 |
| PrivateScope | 0 | 参照できないメンバー。 |
| Private | 1 | プライベートメンバー。 |
| FamANDAssem | 2 | プライベートおよびアセンブリスコープのメンバー。 |
| Assembly | 3 | アセンブリスコープのメンバー。 |
| Family | 4 | 型およびサブタイプからアクセス可能なメンバー。 |
| FamORAssem | 5 | 型、サブタイプ、およびアセンブリからアクセス可能なメンバー。 |
| Public | 6 | 誰でもアクセスできるメンバー。 |
| Static | 16 | インスタンスメンバーとは対照的な静的メンバー。 |
| InitOnly | 32 | 初期化のみ可能で変更できない定数メンバー。 |
| Literal | 64 | コンパイル時定数メンバー。 |
| NotSerialized | 128 | シリアライズされないメンバー。 |
| SpecialName | 512 | 以下の名前のいずれかの特別なフィールド。 |
| PinvokeImpl | 8192 | インターオペラビリティ転送実装。 |
| ReservedMask | 38144 | ランタイムでのみ使用される予約フラグ。 |
| RTSpecialName | 1024 | ランタイムは名前エンコーディングをチェックすべきです。 |
| HasFieldMarshal | 4096 | マーシャリング情報が存在します。 |
| HasDefault | 32768 | 既定値が存在します。 |
| HasFieldRVA | 256 | RVA が存在します。 |

## 参照

* 名前空間 [System::Reflection](../)
* ライブラリ [Aspose.Slides](../../)