---
title: PresentationInfo
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーション ファイルに関する情報
type: docs
url: /ja/com.aspose.slides/presentationinfo/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

プレゼンテーション ファイルの情報
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | バインドされたプレゼンテーションが暗号化されている場合は True を取得し、そうでない場合は False を取得します。 |
| [isPasswordProtected()](#isPasswordProtected--) | バインドされたプレゼンテーションが開くためのパスワードで保護されているかどうかを示す値を取得します。 |
| [isWriteProtected()](#isWriteProtected--) | バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。 |
| [getLoadFormat()](#getLoadFormat--) | バインドされたプレゼンテーションの形式を取得します。 |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | 開くパスワードで保護されたプレゼンテーションのパスワードが正しいかどうかを確認します。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 書き込み保護されたプレゼンテーションの変更用パスワードが正しいかどうかを確認します。 |
| [readDocumentProperties()](#readDocumentProperties--) | バインドされたプレゼンテーションのドキュメント プロパティを取得します。 |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | バインドされたプレゼンテーションのプロパティを更新します。 |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | バインドされたプレゼンテーションをストリームに書き込みます。 |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | バインドされたプレゼンテーションをファイルに書き込みます。 |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

バインドされたプレゼンテーションが暗号化されている場合は True を取得し、そうでない場合は False を取得します。読み取り専用 boolean.

**戻り値:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

バインドされたプレゼンテーションが開くためのパスワードで保護されているかどうかを示す値を取得します。

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**戻り値:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

---

プレゼンテーションが開くためのパスワードで保護されている場合、プロパティ値は NotDefined になります。

**戻り値:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

バインドされたプレゼンテーションの形式を取得します。読み取り専用 [LoadFormat](../../com.aspose.slides/loadformat)。

**戻り値:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

開くパスワードで保護されたプレゼンテーションのパスワードが正しいかどうかを確認します。

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | java.lang.String | チェックするパスワード。 |

パスワードが null または空の場合、このメソッドは false を返します。 |

**戻り値:**
boolean - プレゼンテーションが開くパスワードで保護され、かつパスワードが正しい場合は True、そうでない場合は false を返します。
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

書き込み保護されたプレゼンテーションの変更用パスワードが正しいかどうかを確認します。

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| password | java.lang.String | チェックするパスワード。 |

1. このメソッドを呼び出す前に (\#isWriteProtected.isWriteProtected) プロパティを確認すべきです。 2. パスワードが null または空の場合、このメソッドは false を返します。 |

**戻り値:**
boolean - プレゼンテーションが書き込み保護され、かつパスワードが正しい場合は True、そうでない場合は False を返します。
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

バインドされたプレゼンテーションのドキュメント プロパティを取得します。

**戻り値:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

バインドされたプレゼンテーションのプロパティを更新します。

> ```
> このサンプルは、#updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDDocumentProperties) メソッドを呼び出す方法を示します。
>  #readDocumentProperties.readDocumentProperties メソッドの呼び出しで返されたドキュメント プロパティを更新します。

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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

バインドされたプレゼンテーションをストリームに書き込みます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ストリームはシーク可能で書き込み可能である必要があります。 |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

バインドされたプレゼンテーションをファイルに書き込みます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | java.lang.String | プレゼンテーション ファイル。 |