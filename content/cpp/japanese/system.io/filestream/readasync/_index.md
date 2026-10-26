---
title: ReadAsync()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のストリームからバイト列を非同期で読み取り、読み取ったバイト数分ストリーム内の位置を進め、キャンセル要求を監視します。
type: docs
weight: 196
url: /ja/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) メソッド

現在のストリームからバイトのシーケンスを非同期で読み取り、読み取ったバイト数分だけストリーム内の位置を進め、キャンセル要求を監視します。

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 読み取ったバイトを書き込むためのバイト配列です。 |
| offset | **int32_t** | **buffer** の0ベースの開始書き込み位置です。 |
| count | **int32_t** | 読み取るバイト数です。 |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | キャンセル要求を監視するトークンです。 |

### 戻り値

非同期読み取り操作を表すタスクです。TResult パラメータの値にはバッファに読み込まれたバイトの総数が含まれます。利用可能なバイト数が要求された数未満の場合、結果の値は要求されたバイト数未満になることがあり、ストリームの末尾に達した場合は 0（ゼロ）になることがあります。

## 参考

* 型定義 [RTaskPtr](../../../system/rtaskptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [CancellationToken](../../../system.threading/cancellationtoken/)
* クラス [FileStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)