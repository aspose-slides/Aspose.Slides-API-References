---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
description: プレゼンテーション ファイルに関する情報
type: docs
url: /ja/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

プレゼンテーション ファイルに関する情報
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | バインドされたプレゼンテーションが暗号化されている場合は True を取得し、そうでない場合は False を取得します。 |
| [isPasswordProtected()](#isPasswordProtected--) | バインドされたプレゼンテーションが開くためのパスワードで保護されているかどうかを示す値を取得します。 |
| [isWriteProtected()](#isWriteProtected--) | バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。 |
| [getLoadFormat()](#getLoadFormat--) | バインドされたプレゼンテーションの形式を取得します。 |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | 開くパスワードで保護されたプレゼンテーションのパスワードが正しいかどうかを確認します。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 書き込み保護されたプレゼンテーションの変更パスワードが正しいかどうかを確認します。 |
| [readDocumentProperties()](#readDocumentProperties--) | バインドされたプレゼンテーションのドキュメント プロパティを取得します。 |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | バインドされたプレゼンテーションのプロパティを更新します。 |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | バインドされたプレゼンテーションを書き込みストリームに出力します。 |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | バインドされたプレゼンテーションを書き込みファイルに出力します。 |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

バインドされたプレゼンテーションが暗号化されている場合は True を取得し、そうでない場合は False を取得します。読み取り専用 boolean.

**戻り値:**
boolean

### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

バインドされたプレゼンテーションが開くためのパスワードで保護されているかどうかを示す値を取得します。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**戻り値:**
boolean

### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

プレゼンテーションが開くパスワードで保護されている場合、プロパティ値は NotDefined になります。[NullableBool](../../com.aspose.slides/nullablebool) 列挙体を参照してください。

**戻り値:**
byte

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

バインドされたプレゼンテーションの形式を取得します。読み取り専用 [LoadFormat](../../com.aspose.slides/loadformat)。

**戻り値:**
int

### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

開くパスワードで保護されたプレゼンテーションのパスワードが正しいかどうかを確認します。

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | java.lang.String | 確認するパスワード。 |

--------------------

パスワードが null または空の場合、このメソッドは false を返します。

**戻り値:**
boolean - プレゼンテーションが開くパスワードで保護されていてパスワードが正しい場合は True、そうでない場合は false。

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

書き込み保護されたプレゼンテーションの変更パスワードが正しいかどうかを確認します。

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | java.lang.String | 確認するパスワード。 |

--------------------

1. このメソッドを呼び出す前に (\#isWriteProtected.isWriteProtected) プロパティを確認する必要があります。 2. パスワードが null または空の場合、このメソッドは false を返します。

**戻り値:**
boolean - プレゼンテーションが書き込み保護されていてパスワードが正しい場合は True。そうでない場合は False。

### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

バインドされたプレゼンテーションのドキュメント プロパティを取得します。

**戻り値:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Document properties [IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

バインドされたプレゼンテーションのプロパティを更新します。

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Document properties [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

バインドされたプレゼンテーションを書き込みストリームに出力します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ストリームはシーク可能かつ書き込み可能である必要があります。 |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

バインドされたプレゼンテーションを書き込みファイルに出力します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | プレゼンテーション ファイル。 |