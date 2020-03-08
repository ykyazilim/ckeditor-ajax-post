# ckeditor-ajax-post
/////////// Türkçe  ///////////

zengin metin ediörü olan ckeditör ile ajax kullanmaya çalıştığınız zaman post işleminde gecikmeler meydana gelmektedir bu gecikmeyi
çözmek için ajax işleminizde bu for'u kullanmanız gerekmektedir.

  /////////// English ///////////////////
  
  when you try to use ajax with the rich text editor ckediter, post processing delays occur.
To solve this, you need to use this for your ajax transaction.

                   for (var form in CKEDITOR.instances) 
					        CKEDITOR.instances[form].updateElement();
                  
 /////////////////// EXAMPLE //////////////////
 demo 1: https://yusufkarakaya.com.tr/ckeditor-ajax
 demo 2: https://ykyazilim.github.io/ckeditor-ajax-post/
 
 
