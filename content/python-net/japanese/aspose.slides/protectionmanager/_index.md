---
title: ProtectionManager class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/protectionmanager/
---
## ProtectionManager クラス

プレゼンテーションのパスワード保護管理。

ProtectionManager 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/ja/aspose.slides/protectionmanager/encrypt_document_properties/) | このプロパティは、プレゼンテーションがパスワードで保護されている場合に意味があります。<br/>            true の場合、ドキュメント プロパティはプレゼンテーション ファイル内で暗号化されます。<br/>            false の場合、プレゼンテーションは暗号化されている間、ドキュメント プロパティは公開されます。<br/>            読み取り/書き込み **bool**. |
| [`is_encrypted`](/slides/python-net/ja/aspose.slides/protectionmanager/is_encrypted/) | このインスタンスが暗号化されているかどうかを示す値を取得します。<br/>            読み取り専用 **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/ja/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | このプロパティは、プレゼンテーション ファイルがパスワードで保護され、かつこのファイルのドキュメント <br/>            プロパティが公開されている場合に意味があります。<br/>            true の場合、パスワードを使用せずに暗号化されたプレゼンテーション ファイルからドキュメント プロパティのみがロードされることを意味します。<br/>            false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体がロードされ、ドキュメント プロパティだけでなくすべてがロードされることを意味します。<br/>            プレゼンテーションが暗号化されていない場合、このプロパティの値は常に false です。<br/>            暗号化されたファイルのドキュメント プロパティが公開されていない場合、このプロパティの値は常に false です。<br/>            Presentation.EncryptDocumentProperties が true の場合、IsOnlyDocumentPropertiesLoaded プロパティの値は常に false です。<br/>            読み取り専用 **bool**. |
| [`is_write_protected`](/slides/python-net/ja/aspose.slides/protectionmanager/is_write_protected/) | このプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。<br/>            読み取り専用 **bool**. |
| [`encryption_password`](/slides/python-net/ja/aspose.slides/protectionmanager/encryption_password/) | プレゼンテーションの暗号化に使用されるパスワードを取得します。<br/>            読み取り専用 **str**. |
| [`read_only_recommended`](/slides/python-net/ja/aspose.slides/protectionmanager/read_only_recommended/) | 読み取り専用の推奨設定を取得または設定します。<br/>            読み取り/書き込み **bool**. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/ja/aspose.slides/protectionmanager/encrypt/#str) | 指定されたパスワードでプレゼンテーションを暗号化します。 |
| [`remove_encryption(self)`](/slides/python-net/ja/aspose.slides/protectionmanager/remove_encryption/#) | 暗号化を解除します。 |
| [`set_write_protection(self, password)`](/slides/python-net/ja/aspose.slides/protectionmanager/set_write_protection/#str) | 指定されたパスワードでこのプレゼンテーションに書き込み保護を設定します。 |
| [`remove_write_protection(self)`](/slides/python-net/ja/aspose.slides/protectionmanager/remove_write_protection/#) | このプレゼンテーションの書き込み保護を解除します。 |
| [`check_write_protection(self, password)`](/slides/python-net/ja/aspose.slides/protectionmanager/check_write_protection/#str) | プレゼンテーションが変更のためにパスワードで保護されているかどうかを判断します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)