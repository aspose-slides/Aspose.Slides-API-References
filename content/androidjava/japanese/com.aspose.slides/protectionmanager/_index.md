---
title: ProtectionManager
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーションのパスワード保護管理。
type: docs
url: /ja/com.aspose.slides/protectionmanager/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

プレゼンテーションのパスワード保護管理。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | プレゼンテーションがパスワードで保護されている場合に意味のあるプロパティです。 |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | プレゼンテーションがパスワードで保護されている場合に意味のあるプロパティです。 |
| [isEncrypted()](#isEncrypted--) | このインスタンスが暗号化されているかどうかを示す値を取得します。 |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | プレゼンテーションファイルがパスワードで保護され、かつこのファイルのドキュメントプロパティが公開されている場合に意味のあるプロパティです。 |
| [isWriteProtected()](#isWriteProtected--) | このプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。 |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | 指定されたパスワードでプレゼンテーションを暗号化します。 |
| [removeEncryption()](#removeEncryption--) | 暗号化を解除します。 |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | 指定されたパスワードでこのプレゼンテーションに書き込み保護を設定します。 |
| [removeWriteProtection()](#removeWriteProtection--) | このプレゼンテーションの書き込み保護を解除します。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | プレゼンテーションが変更のためにパスワードで保護されているかどうかを判定します。 |
| [getEncryptionPassword()](#getEncryptionPassword--) | プレゼンテーションの暗号化に使用されるパスワードを取得します。 |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | 読み取り専用の推奨設定を取得または設定します。 |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | 読み取り専用の推奨設定を取得または設定します。

### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

このプロパティは、プレゼンテーションがパスワードで保護されている場合に意味があります。true の場合、ドキュメントプロパティはプレゼンテーションファイル内で暗号化されます。false の場合、プレゼンテーションは暗号化されているがドキュメントプロパティは公開されます。読み書き可能なブール値。

**戻り値:**
boolean

### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

このプロパティは、プレゼンテーションがパスワードで保護されている場合に意味があります。true の場合、ドキュメントプロパティはプレゼンテーションファイル内で暗号化されます。false の場合、プレゼンテーションは暗号化されているがドキュメントプロパティは公開されます。読み書き可能なブール値。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

このインスタンスが暗号化されているかどうかを示す値を取得します。読み取り専用のブール値。

値: プレゼンテーションが暗号化ファイルからロードされた場合または \#encrypt(String).encrypt(String) メソッドが呼び出された場合は true; それ以外の場合は false。

**戻り値:**
boolean

### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

このプロパティは、プレゼンテーションファイルがパスワードで保護され、かつこのファイルのドキュメントプロパティが公開されている場合に意味があります。true の場合、パスワードを使用せずに暗号化されたプレゼンテーションファイルからドキュメントプロパティのみがロードされます。false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体がロードされ、ドキュメントプロパティだけでなく全体がロードされます。プレゼンテーションが暗号化されていない場合、プロパティ値は常に false です。暗号化されたファイルのドキュメントプロパティが公開されていない場合、プロパティ値は常に false です。Presentation.EncryptDocumentProperties が true の場合、IsOnlyDocumentPropertiesLoaded プロパティ値は常に false です。読み取り専用のブール値。

**戻り値:**
boolean

### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

このプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。読み取り専用のブール値。

**戻り値:**
boolean

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

指定されたパスワードでプレゼンテーションを暗号化します。

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| encryptionPassword | java.lang.String | パスワード。 |

### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

暗号化を解除します。

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

指定されたパスワードでこのプレゼンテーションに書き込み保護を設定します。

> ```
> 以下のサンプルコードは、プレゼンテーションに書き込み保護を設定する方法を示しています。
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| password | java.lang.String | パスワード。 |

### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

このプレゼンテーションの書き込み保護を解除します。

> ```
> このサンプルコードは、PowerPoint プレゼンテーションから書き込み保護を削除する方法を示しています。
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

プレゼンテーションが変更のためにパスワードで保護されているかどうかを判定します。

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| password | java.lang.String | 確認用のパスワード。 |
1. このメソッドを呼び出す前に (\#isWriteProtected.isWriteProtected) プロパティを確認すべきです。 2. パスワードが null または空文字列の場合、このメソッドは false を返します。 |

**戻り値:**
boolean - パスワードが有効な場合は True、そうでない場合は false。

### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

プレゼンテーションの暗号化に使用されるパスワードを取得します。読み取り専用の文字列。

**戻り値:**
java.lang.String

### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

読み取り専用の推奨設定を取得または設定します。読み書き可能なブール値。

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
boolean

### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

読み取り専用の推奨設定を取得または設定します。読み書き可能なブール値。

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |