---
title: Videos
second_title: Αναφορά API Aspose.Sildes για .NET
description: Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. Μόνο προς ανάγνωση IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /el/aspose.slides/presentation/videos/
---
## Presentation.Videos ιδιότητα

Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. Μόνο προς ανάγνωση [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε ενσωματωμένο Video Frame σε μια PowerPoint Presentation.

```csharp
[C#]
// Δημιουργία αντικειμένου Presentation που αντιπροσωπεύει το PPTX
using (Presentation pres = new Presentation())
{
    // Λήψη της πρώτης διαφάνειας
    ISlide sld = pres.Slides[0];
    // Ενσωμάτωση βίντεο στην παρουσίαση
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Προσθήκη Video Frame
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Ορισμός του βίντεο στο Video Frame
    vf.EmbeddedVideo = vid;
    // Ορισμός Λειτουργίας Αναπαραγωγής και Έντασης του Video
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Αποθήκευση του αρχείου PPTX στον δίσκο
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα βίντεο παρέχοντας τη διαδρομή του αρχείου βίντεο απευθείας στη μέθοδο AddVideoFrame για μια PowerPoint Presentation.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε μεγάλο αρχείο μέσω BLOB σε μια Presentation.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Δημιουργεί μια νέα παρουσίαση στην οποία θα προστεθεί το βίντεο
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Ας προσθέσουμε το βίντεο στην παρουσίαση - επιλέξαμε τη συμπεριφορά KeepLocked επειδή δεν
        // προοριζόμαστε να προσπελάσουμε το αρχείο "veryLargeVideo.avi".
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Αποθηκεύει την παρουσίαση. Ενώ μια μεγάλη παρουσίαση εξάγεται, η κατανάλωση μνήμης
        // παραμένει χαμηλή καθ' όλη τη διάρκεια ζωής του αντικειμένου pres
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Το παρακάτω παράδειγμα δείχνει πώς να εξάγετε μεγάλο αρχείο μέσω BLOB από μια PowerPoint Presentation.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Κλειδώνει το αρχείο προέλευσης και ΔΕΝ το φορτώνει στη μνήμη
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Δημιουργεί μια παρουσίαση, κλειδώνει το αρχείο "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Ας αποθηκεύσουμε κάθε βίντεο σε αρχείο. Για να αποτρέψουμε υψηλή χρήση μνήμης, χρειαζόμαστε ένα buffer που θα χρησιμοποιηθεί
	// για τη μεταφορά των δεδομένων από τη ροή βίντεο της παρουσίασης σε ροή για ένα νέο αρχείο βίντεο.
	byte[] buffer = new byte[8 * 1024];
	// Επανάληψη μέσω των βίντεο
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Ανοίγει τη ροή βίντεο της παρουσίασης. Παρακαλώ σημειώστε ότι αποφεύγουμε σκόπιμα την πρόσβαση σε ιδιότητες
		// όπως video.BinaryData - επειδή αυτή η ιδιότητα επιστρέφει έναν πίνακα byte που περιέχει ολόκληρο το βίντεο, το οποίο στη συνέχεια
		// προκαλεί τη φόρτωση byte στη μνήμη. Χρησιμοποιούμε το video.GetStream, το οποίο επιστρέφει Stream - και ΔΕΝ
		//  απαιτεί να φορτώσουμε ολόκληρο το βίντεο στη μνήμη.
		using (Stream presVideoStream = video.GetStream())
		{
			using (FileStream outputFileStream = File.OpenWrite($"video{index}.avi"))
			{
				int bytesRead;
				while ((bytesRead = presVideoStream.Read(buffer, 0, buffer.Length)) > 0)
				{
					outputFileStream.Write(buffer, 0, bytesRead);
				}
			}
		}
		// Η κατανάλωση μνήμης θα παραμείνει χαμηλή ανεξάρτητα από το μέγεθος του βίντεο ή της παρουσίασης,
	}
	// Εάν είναι απαραίτητο, μπορείτε να εφαρμόσετε τα ίδια βήματα για αρχεία ήχου.
}
```

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε έναν υπερσύνδεσμο σε ένα βίντεο σε μια PowerPoint Presentation.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IVideo video = pres.Videos.AddVideo(File.ReadAllBytes("video.avi"));
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 100, 100, video);
    videoFrame.HyperlinkClick = new Hyperlink("https://www.aspose.com/");
    videoFrame.HyperlinkClick.Tooltip = "More than 70% Fortune 100 companies trust Aspose APIs";
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε Video Frame με Video από Web Source σε μια PowerPoint Presentation.

```csharp
[C#]
public static void Run()
{
    using (Presentation pres = new Presentation())
    {
        AddVideoFromYouTube(pres, "Tj75Arhq5ho");
        pres.Save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
    }
}
private static void AddVideoFromYouTube(Presentation pres, string videoId)
{
    //προσθήκη videoFrame
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //φόρτωση μικρογραφίας
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Το παρακάτω παράδειγμα δείχνει πώς να εξαγάγετε Video από διαφάνεια μιας PowerPoint Presentation.

```csharp
[C#]
// Δημιουργία αντικειμένου Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
using (Presentation presentation = new Presentation("Video.pptx"))
{
	foreach (ISlide slide in presentation.Slides)
	{
		foreach (IShape shape in presentation.Slides[0].Shapes)
		{
			if (shape is VideoFrame)
			{
				IVideoFrame vf = shape as IVideoFrame;
				String type = vf.EmbeddedVideo.ContentType;
				int ss = type.LastIndexOf('/');
				type = type.Remove(0, type.LastIndexOf('/') + 1);
				Byte[] buffer = vf.EmbeddedVideo.BinaryData;
				using (FileStream stream = new FileStream("NewVideo_out." + type, FileMode.Create, FileAccess.Write, FileShare.Read))
				{
					stream.Write(buffer, 0, buffer.Length);
				}
			}
		}
	}
}
```

### Δείτε επίσης

* διασύνδεση [IVideoCollection](../../ivideocollection)
* κλάση [Presentation](../../presentation)
* χώρο ονομάτων [Aspose.Slides](../../presentation)
* συγκρότηση [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->