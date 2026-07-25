---
title: CipherMode
second_title: Aspose.Slides for C++ API リファレンス
description: ブロック暗号モード。
type: docs
weight: 885
url: /ja/system.security.cryptography/ciphermode/
---
## CipherMode 列挙体

ブロック暗号モード。

```cpp
enum class CipherMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| CBC | 1 | 現在のブロックと前のブロックを組み合わせて暗号化を向上させる暗号ブロック連鎖。 |
| ECB | 2 | ブロック間の影響がない電子コードブックモード。暗号化が弱くなる。 |
| OFB | 3 | 大きな入力ブロックを小さな部分に分割して処理する出力フィードバックモード。 |
| CFB | 4 | 大きな入力ブロックを小さな部分に分割して処理する暗号フィードバックモード。変形ルールはOFBとは異なる。 |
| CTS | 5 | 暗号テキスト盗用モードで、最後の2ブロックを除くすべてでCBCと同様に動作する。 |

## 参照

* 名前空間 [System::Security::Cryptography](../)
* ライブラリ [Aspose.Slides](../../)