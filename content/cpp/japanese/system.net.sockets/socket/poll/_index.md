---
title: Poll()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたポーリングモードに基づくソケットの状態を返します。
type: docs
weight: 742
url: /ja/system.net.sockets/socket/poll/
---
## Socket::Poll(int32_t, SelectMode) メソッド

指定されたポーリングモードに基づくソケットの状態を返します。

```cpp
bool System::Net::Sockets::Socket::Poll(int32_t microSeconds, SelectMode mode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| microSeconds | **int32_t** | レスポンスを待つミリ秒単位の時間量。 |
| mode | [SelectMode](../../selectmode/) | ポーリングモード。 |

### 戻り値

指定されたポーリングモードに基づくソケットの状態。

## 参照

* 列挙体 [SelectMode](../../selectmode/)
* クラス [Socket](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)