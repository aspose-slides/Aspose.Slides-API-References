---
title: GetLeapMonth()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された年のうるう月を取得します。
type: docs
weight: 274
url: /ja/system.globalization/calendar/getleapmonth/
---
## Calendar::GetLeapMonth(int) const メソッド


指定された年のうるう月を取得します。

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| year | int | うるう月を取得する対象の年。 |

### 戻り値

指定された年のうるう月、うるう月が存在しない場合は 0 が返されます。

## Calendar::GetLeapMonth(int, int) const メソッド


指定された年のうるう月を取得します。

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const =0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| year | int | うるう月を取得する対象の年。 |
| era | int | 時代。 |

### 戻り値

指定された時代の指定された年のうるう月、うるう月が存在しない場合は 0 が返されます。

## 参照

* クラス [Calendar](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)