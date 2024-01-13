
https://om376.github.io/taxi-fast/


WA.onMessage(function (message) { 32 if (message.type === 'image') { 33 var imageURL = message.content; 34 var downloadURL = WA.downloadContent(imageURL); 35 WA.shareDownloadLink(downloadURL); 36 } 37 });
