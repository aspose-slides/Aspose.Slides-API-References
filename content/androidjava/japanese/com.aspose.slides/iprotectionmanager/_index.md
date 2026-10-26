---
title: IProtectionManager
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーションのパスワード保護管理。
type: docs
url: /ja/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

プレゼンテーションのパスワード保護管理。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | このプロパティは、プレゼンテーションがパスワードで保護されている場合に意味があります。 |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | このプロパティは、プレゼンテーションがパスワードで保護されている場合に意味があります。 |
| [isEncrypted()](#isEncrypted--) | このインスタンスが暗号化されているかどうかを示す値を取得します。 |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | このプロパティは、プレゼンテーションファイルがパスワードで保護され、かつこのファイルのドキュメントプロパティが公開されている場合に意味があります。 |
| [isWriteProtected()](#isWriteProtected--) | このプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。 |
| [getEncryptionPassword()](#getEncryptionPassword--) | 暗号化パスワードを返します。 |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | 読み取り専用推奨設定を取得または設定します。 |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | 読み取り専用推奨設定を取得または設定します。 |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | 指定されたパスワードでプレゼンテーションを暗号化します。 |
| [removeEncryption()](#removeEncryption--) | 暗号化を解除します。 |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | 指定されたパスワードでこのプレゼンテーションに書き込み保護を設定します。 |
| [removeWriteProtection()](#removeWriteProtection--) | このプレゼンテーションの書き込み保護を解除します。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | プレゼンテーションが変更のためにパスワードで保護されているかどうかを判断します。 |

### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

このプロパティは、プレゼンテーションがパスワードで保護されている場合に意味があります。true の場合、ドキュメントプロパティはプレゼンテーションファイル内で暗号化されます。false の場合、プレゼンテーションが暗号化されている間、ドキュメントプロパティは公開されます。読み取り/書き込み可能なブール値です。

**戻り値:**
boolean

### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

このプロパティは、プレゼンテーションがパスワードで保護されている場合に意味があります。true の場合、ドキュメントプロパティはプレゼンテーションファイル内で暗号化されます。false の場合、プレゼンテーションが暗号化されている間、ドキュメントプロパティは公開されます。読み取り/書き込み可能なブール値です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

このインスタンスが暗号化されているかどうかを示す値を取得します。読み取り専用のブール値です。

値: true ならプレゼンテーションが暗号化ファイルからロードされたか、\#encrypt(String).encrypt(String) メソッドが呼び出されたかを示し、そうでなければ false。

**戻り値:**
boolean

### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

このプロパティは、プレゼンテーションファイルがパスワードで保護されており、かつこのファイルのドキュメントプロパティが公開されている場合に意味があります。true の場合、パスワードを使用せずに暗号化されたプレゼンテーションファイルからドキュメントプロパティのみがロードされます。false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体がロードされ、ドキュメントプロパティだけでなくすべてがロードされます。プレゼンテーションが暗号化されていない場合、プロパティ値は常に false です。暗号化されたファイルのドキュメントプロパティが公開されていない場合、プロパティ値は常に false です。PresentationEx.EncryptDocumentProperties が true の場合、IsOnlyDocumentPropertiesLoaded プロパティ値は常に false です。読み取り専用のブール値です。

**戻り値:**
boolean

### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

このプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。読み取り専用のブール値です。

**戻り値:**
boolean

### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

暗号化パスワードを返します。読み取り専用の Stringです。

**戻り値:**
java.lang.String

### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

読み取り専用推奨設定を取得または設定します。読み書き可能なブール値です。

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**戻り値:**
boolean

### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

読み取り専用推奨設定を取得または設定します。読み書き可能なブール値です。

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

指定されたパスワードでプレゼンテーションを暗号化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| encryptionPassword | java.lang.String | パスワード。 |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

暗号化を解除します。

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

指定されたパスワードでこのプレゼンテーションに書き込み保護を設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| password | java.lang.String | パスワード。 |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

このプレゼンテーションの書き込み保護を解除します。

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

プレゼンテーションが変更のためにパスワードで保護されているかどうかを判断します。

--------------------

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
| password | java.lang.String | チェック用のパスワード。 |

1. このメソッドを呼び出す前に (\#isWriteProtected.isWriteProtected) プロパティを確認する必要があります。 2. パスワードが null または空文字列の場合、このメソッドは false を返します. |

**戻り値:**
boolean - パスワードが有効な場合は true、そうでない場合は false。