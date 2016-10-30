# html-
html局部打印代码

//js部分
function printTab(){           bdhtml=window.document.body.innerHTML;              sprnstr="<!--startprint-->";              eprnstr="<!--endprint-->";                prnhtml=bdhtml.substr(bdhtml.indexOf(sprnstr)+17);              prnhtml=prnhtml.substring(0,prnhtml.indexOf(eprnstr));              window.document.body.innerHTML=prnhtml;            window.print();        }
//html部分
<!--startprint--> 
//打印的部分
<!--endprint-->
