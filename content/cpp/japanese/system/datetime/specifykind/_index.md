---
title: SpecifyKind()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された DateTime オブジェクトと同じティック数を表す新しい DateTime オブジェクトを作成し、引数 kind で指定されたローカル時間、UTC 時間、またはどちらでもない時間を表します。
type: docs
weight: 833
url: /ja/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) メソッド

指定された [DateTime](../) オブジェクトと同じティック数を表す新しい [DateTime](../) オブジェクトを作成し、引数 **kind** で指定されたローカル時間、UTC 時間、またはどちらでもない時間を表します。

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [DateTime](../) | ティック数をコピーする元となる [DateTime](../) オブジェクト |
| kind | [DateTimeKind](../../datetimekind/) | 新しいオブジェクトがローカル時間、UTC 時間、またはどちらでもない時間を表すかを指定します。 |

### 戻り値

**value** と **kind** で指定された DateTimeKind の値と同じティック数を表す新しい [DateTime](../) オブジェクト。

## 参照

* Enum [DateTimeKind](../../datetimekind/)
* クラス [DateTime](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)