---
title: IOControl()
second_title: Aspose.Slides for C++ API リファレンス
description: ソケットの低レベルの動作モードを設定します。
type: docs
weight: 703
url: /ja/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

ソケットの低レベルの動作モードを設定します。

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ioControlCode | **int32_t** | 実行する操作の制御コードです。 |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 入力データを含むバイト配列です。 |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 出力データを含むバイト配列です。 |

### 戻り値

**optionOutValue** パラメータのバイト数です。

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

ソケットの低レベルの動作モードを設定します。

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | 実行する操作の制御コードです。 |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 入力データを含むバイト配列です。 |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 出力データを含むバイト配列です。 |

### 戻り値

**optionOutValue** パラメータのバイト数です。

## 参照

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [Socket](../)
* 名前空間 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)