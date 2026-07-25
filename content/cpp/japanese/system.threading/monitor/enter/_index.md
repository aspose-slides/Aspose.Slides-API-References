---
title: Enter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたオブジェクトに対して排他ロックを取得します。
type: docs
weight: 1
url: /ja/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) メソッド

指定されたオブジェクトに対して排他ロックを取得します。

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | モニターロックを取得する対象のオブジェクトです。 |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) メソッド

指定されたオブジェクトに対して排他ロックを取得し、ロックが取得されたかどうかを示す値を原子的に設定します。

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## See Also

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [Monitor](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)