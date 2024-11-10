# rdp_holiday
https://www.youtube.com/watch?v=ceR4TDuqE5A

# Install
```pip3 install git+https://github.com/wmetcalf/rdp_holiday.git -U```

# Example
```
 rdp_holiday -i /home/coz/Downloads/badrdp/f357d26265a59e9c356be5a8ddb8d6533d1de222aae969c2ad4dc9c40863bfe8.rdp -o ./bad.json
 cat bad.json
{
    "alternate_full_address": "us-west-1.aws-ukraine.cloud",
    "full_address": "us-west-1.aws-ukraine.cloud",
    "drivestoredirect": "*",
    "redirectprinters": "1",
    "redirectcomports": "1",
    "redirectsmartcards": "1",
    "redirectwebauthn": "1",
    "redirectclipboard": "1",
    "audiocapturemode": "1",
    "remoteapplicationicon": "C:\\Windows\\SystemApps\\Microsoft.Windows.SecHealthUI_cw5n1h2txyewy\\Assets\\Health.contrast-white.ico",
    "remoteapplicationmode": "1",
    "remoteapplicationname": "AWS Secure Storage Connection Stability Test v24091285697854",
    "remoteapplicationexpandcmdline": "0",
    "remoteapplicationcmdline": "%USERPROFILE% %COMPUTERNAME% %USERDNSDOMAIN%",
    "remoteapplicationprogram": "||AWS Secure Storage Connection Stability Test v24091285697854",
    "audiomode": "0",
    "screen_mode_id": "1",
    "compression": "1",
    "keyboardhook": "2",
    "videoplaybackmode": "1",
    "networkautodetect": "1",
    "bandwidthautodetect": "1",
    "autoreconnection_enabled": "1",
    "authentication_level": "2",
    "gatewayusagemethod": "4",
    "gatewaycredentialssource": "4",
    "gatewayprofileusagemethod": "0",
    "promptcredentialonce": "0",
    "enablerdsaadauth": "0",
    "redirectlocation": "0",
    "signscope": "Full Address,Alternate Full Address,Use Redirection Server Name,Negotiate Security Layer,AutoReconnection Enabled,GatewayHostname,GatewayUsageMethod,GatewayProfileUsageMethod,GatewayCredentialsSource,PromptCredentialOnce,Alternate Shell,Shell Working Directory,RemoteApplicationProgram,RemoteApplicationMode,RemoteApplicationName,RemoteApplicationIcon,RemoteApplicationCmdLine,RemoteApplicationExpandCmdLine,Prompt For Credentials,Authentication Level,AudioMode,RedirectPrinters,RedirectCOMPorts,RedirectSmartCards,RedirectPOSDevices,RedirectClipboard,DrivesToRedirect,RDGIsKDCProxy,KDCProxyName,EnableRdsAadAuth,RedirectWebAuthn",
    "signature": "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",
    "signscope_but_missing_sig": false,
    "certificate_truncated_or_invalid": false,
    "certificates": [
        {
            "subject": "CN=aws-ukraine.cloud",
            "issuer": "CN=E5,O=Let's Encrypt,C=US",
            "not_before": "2024-09-26T11:43:47+00:00",
            "not_after": "2024-12-25T11:43:46+00:00",
            "serial_number": "265290441101301619611229963166629451659968",
            "fingerprint_sha256": "76449be80b1c7649c22b00b85f05015e33daedb24186cba19d2279828656fa1c",
            "fingerprint_sha1": "e22c838048bb6ca842e8f232a500ee99502b1f19",
            "cert_valid_date": true,
            "subject_alternative_names": [
                "*.aws-ukraine.cloud",
                "aws-ukraine.cloud"
            ]
        },
        {
            "subject": "CN=E5,O=Let's Encrypt,C=US",
            "issuer": "CN=ISRG Root X1,O=Internet Security Research Group,C=US",
            "not_before": "2024-03-13T00:00:00+00:00",
            "not_after": "2027-03-12T23:59:59+00:00",
            "serial_number": "174873564306387906651619802726858882526",
            "fingerprint_sha256": "5dfdb3cf31b26f23d87c09f3a0cef642f64069a9fb7cfe29270bb5dc0f1e16bb",
            "fingerprint_sha1": "5f28d9c589ee4bf31a11b78c72b8d13f079ddc45",
            "cert_valid_date": true,
            "subject_alternative_names": null
        },
        {
            "subject": "CN=ISRG Root X1,O=Internet Security Research Group,C=US",
            "issuer": "CN=ISRG Root X1,O=Internet Security Research Group,C=US",
            "not_before": "2015-06-04T11:04:38+00:00",
            "not_after": "2035-06-04T11:04:38+00:00",
            "serial_number": "172886928669790476064670243504169061120",
            "fingerprint_sha256": "96bcec06264976f37460779acf28c5a7cfe8a3c0aae11a8ffcee05c0bddf08c6",
            "fingerprint_sha1": "cabd2a79a1076a31f21d253635cb039d4329a5e8",
            "cert_valid_date": true,
            "subject_alternative_names": null
        }
    ],
    "certificate_chain_len": 3,
    "signature_hex": "30820e5506092a864886f70d010702a0820e4630820e42020101310f300d06096086480165030402010500300b06092a864886f70d010701a0820d66308203983082031ea0030201020212030b9e58729a780f83b469b3bf5faf4dfac0300a06082a8648ce3d0403033032310b300906035504061302555331163014060355040a130d4c6574277320456e6372797074310b3009060355040313024535301e170d3234303932363131343334375a170d3234313232353131343334365a301c311a3018060355040313116177732d756b7261696e652e636c6f75643059301306072a8648ce3d020106082a8648ce3d03010703420004e3fd996990db64a847cff548fec6b9d33d4ad2fc2b6d88fe3b00731c110e04b372918810f63be8973bd464c006f140543d810854bbf72d33cb8450adaf5a723da382022830820224300e0603551d0f0101ff040403020780301d0603551d250416301406082b0601050507030106082b06010505070302300c0603551d130101ff04023000301d0603551d0e04160414721df73a3907a57c3f0aa8ab51893e561ad02805301f0603551d230418301680149f2b5fcf3c214f9d04b7ed2b2cc4c6708bd2d70d305506082b0601050507010104493047302106082b060105050730018615687474703a2f2f65352e6f2e6c656e63722e6f7267302206082b060105050730028616687474703a2f2f65352e692e6c656e63722e6f72672f30310603551d11042a302882132a2e6177732d756b7261696e652e636c6f756482116177732d756b7261696e652e636c6f756430130603551d20040c300a3008060667810c01020130820104060a2b06010401d6790204020481f50481f200f000770048b0e36bdaa647340fe56a02fa9d30eb1c5201cb56dd2c81d9bbbfab39d88473000001922e5a84b90000040300483046022100be032a034b38a74889c953a5ce69ae00359f73e07cb4bf936c3fbb5e57d24f1b022100cf83d3a373f00b9886ac52afaf35b10a9fcb33d743ab88c9a011502120d8ee6400750076ff883f0ab6fb9551c261ccf587ba34b4a4cdbb29dc68420a9fe6674c5a3a74000001922e5a84f5000004030046304402202612b00a6279685777c4399783f343b0b5b425e36e10b68d9f015413686dcf0c022013df376a63a74e672f11e20c000aa8769b35d015d1645eaa0235324760c353a7300a06082a8648ce3d040303036800306502301365cc9b91254f9c8751edc8a90b1314076b24d2143afae93becae18811e672502284c0c24ef23bae05a6e7bf8286f55023100fa13a91716848d527bd42a759c310312b38b6cd96ded5e0f5b6718e4ca3e6500f5f1fc1a35dfbbe3eab7132efe2e7150308204573082023fa003020102021100838f6c63ceb1398c6206628315c9fdde300d06092a864886f70d01010b0500304f310b300906035504061302555331293027060355040a1320496e7465726e65742053656375726974792052657365617263682047726f7570311530130603550403130c4953524720526f6f74205831301e170d3234303331333030303030305a170d3237303331323233353935395a3032310b300906035504061302555331163014060355040a130d4c6574277320456e6372797074310b30090603550403130245353076301006072a8648ce3d020106052b81040022036200040d0b3a8a6b618eb6efdc5f58e7c6424554ab63f66661480a2e5975b481023750b73f1679dc98eca1289772201c2ccfd57c52204e54785b84146bc090ae85ecc051413c5a877f064dd4fe60d1fa6c2de17d951088a208540f991a4ce6ea0aacd8a381f83081f5300e0603551d0f0101ff040403020186301d0603551d250416301406082b0601050507030206082b0601050507030130120603551d130101ff040830060101ff020100301d0603551d0e041604149f2b5fcf3c214f9d04b7ed2b2cc4c6708bd2d70d301f0603551d2304183016801479b459e67bb6e5e40173800888c81a58f6e99b6e303206082b0601050507010104263024302206082b060105050730028616687474703a2f2f78312e692e6c656e63722e6f72672f30130603551d20040c300a3008060667810c01020130270603551d1f0420301e301ca01aa0188616687474703a2f2f78312e632e6c656e63722e6f72672f300d06092a864886f70d01010b050003820201001f729d34454241daa4d0b2b2b8d2264ca751258d42daec364896a3ba1aa4c863d8f02fb3cecb9f67e9a09e19ead40d8a550392ca43849d46f1d5ccbadfbac1022871f7bafe6dcc1b64ceac4c321a12b891fcf2e4e8b2acf417b4ba857180e2837291bdb2f0f7dc9f86f4b71fbf52bd96e0e6493806e9734520de6f7c8e60b3f94c3f2a2310c748ccaf5b95c976ff5bcac4ef16182723bec4359c9fcfc2df0b41905f385c955cff2e6c0a7f6aeddd73810a586f4c3b9cdcc75a93f7e3574467555b11af98115101a8dc88c7d7304d59b869a4dff18e92800ced992366695eca890fd4b1b399f25c51df6cede7aed7ff7f7a0e5795777fe791ad62300cf82e031b98bb79a36a726d85fb2c5820fb7a71b6ed6153490867c75aa1c44381584ad532167bfcb23caa53cca981968d27d69571648808b388135fd0bffee82ac9d909627ddbac14e91a86d4e60f18e8b5cee00184bc3ad5cb8f5434f6f27412fdeeb3f797095ead1e2b505c689e9f259b266e34600f9a779af11fe6f75033b30212f534b476ecc762399871c9a000476fc2950605a9fe571719689669e3b207b44ff8e7c3b6f8b63ac6a9c57895eef355b3b7cc96b4636358e829aaa69b272706f02ad780046edc8bb157ce4bae81f1aa647855f6358e173c4615e194827bc5473eb76b111936c082c6dd3fc41a648890261550c4a78e625d5500fd17a35affece65c273082056b30820353a0030201020211008210cfb0d240e3594463e0bb63828b00300d06092a864886f70d01010b0500304f310b300906035504061302555331293027060355040a1320496e7465726e65742053656375726974792052657365617263682047726f7570311530130603550403130c4953524720526f6f74205831301e170d3135303630343131303433385a170d3335303630343131303433385a304f310b300906035504061302555331293027060355040a1320496e7465726e65742053656375726974792052657365617263682047726f7570311530130603550403130c4953524720526f6f7420583130820222300d06092a864886f70d01010105000382020f003082020a0282020100ade82473f41437f39b9e2b57281c87bedcb7df38908c6e3ce657a078f775c2a2fef56a6ef6004f28dbde68866c4493b6b163fd14126bbf1fd2ea319b217ed1333cba48f5dd79dfb3b8ff12f1219a4bc18a8671694a66666c8f7e3c70bfad292206f3e4c0e680aee24b8fb7997e94039fd347977c99482353e838ae4f0a6f832ed149578c8074b6da2fd0388d7b0370211b75f2303cfa8faeddda63abeb164fc28e114b7ecf0be8ffb5772ef4b27b4ae04c12250c708d0329a0e15324ec13d9ee19bf10b34a8c3f89a36151deac870794f46371ec2ee26f5b9881e1895c34796c76ef3b906279e6dba49a2f26c5d010e10eded9108e16fbb7f7a8f7c7e50207988f360895e7e237960d36759efb0e72b11d9bbc03f94905d881dd05b42ad641e9ac0176950a0fd8dfd5bd121f352f28176cd298c1a80964776e4737baceac595e689d7f72d689c50641293e593edd26f524c911a75aa34c401f46a199b5a73a516e863b9e7d72a712057859ed3e5178150b038f8dd02f05b23e7b4a1c4b730512fcc6eae050137c439374b3ca74e78e1f0108d030d45b7136b407bac130305c48b7823b98a67d608aa2a32982ccbabd83041ba2830341a1d605f11bc2b6f0a87c863b46a8482a88dc769a76bf1f6aa53d198feb38f364dec82b0d0a28fff7dbe21542d422d0275de179fe18e77088ad4ee6d98b3ac6dd27516effbc64f533434f0203010001a3423040300e0603551d0f0101ff040403020106300f0603551d130101ff040530030101ff301d0603551d0e0416041479b459e67bb6e5e40173800888c81a58f6e99b6e300d06092a864886f70d01010b05000382020100551f58a9bcb2a850d00cb1d81a6920272908ac61755c8a6ef882e5692fd5f6564bb9b8731059d321977ee74c71fbb2d260ad39a80bea17215685f1500e59ebcee059e9bac915ef869d8f8480f6e4e99190dc179b621b45f06695d27c6fc2ea3bef1fcfcbd6ae27f1a9b0c8aefd7d7e9afa2204ebffd97fea912b22b1170e8ff28a345b58d8fc01c954b9b826cc8a8833894c2d843c82dfee965705ba2cbbf7c4b7c74e3b82be31c822737392d1c280a43939103323824c3c9f86b255981dbe29868c229b9ee26b3b573a82704ddc09c789cb0a074d6ce85d8ec9efceabc7bbb52b4e45d64ad026cce572ca086aa595e315a1f7a4edc92c5fa5fbffac28022ebed77bbbe3717b9016d3075e46537c3707428cd3c4969cd599b52ae0951a8048ae4c3907cecc47a452952bbab8fbadd233537de51d4d6dd5a1b1c7426fe64027355ca328b7078de78d3390e7239ffb509c796c46d5b415b3966e7e9b0c963ab8522d3fd65be1fb08c284fe24a8a389daac6ae1182ab1a843615bd31fdc3b8d76f22de88d75df17336c3d53fb7bcb415fffdca2d06138e196b8ac5d8b37d775d533c09911ae9d41c1727584be0241425f67244894d19b27be073fb9b84f817451e17ab7ed9d23e2bee0d52804133c31039edd7a6c8fc60718c67fde478e3f289e0406cfa5543477bdec899be91743df5bdb5ffe8e1e57a2cd409d7e6222dade18273181b43081b102010130483032310b300906035504061302555331163014060355040a130d4c6574277320456e6372797074310b30090603550403130245350212030b9e58729a780f83b469b3bf5faf4dfac0300d06096086480165030402010500300b06072a8648ce3d020105000446304402203e5c0c55970c5d82ab3ec079df51259184e9b3e70f731ad1550665a5e2bb6bf602206da8901925cf66e297898312c8801f7b3ef40717e26e8f7a3a6fdbeff499b717",
    "signature_sha1": "cfdb5de37ae9517fdfa031e95de538c9f13584d6",
    "signature_sha256": "50b280eca4e2d5cf2feff0e0401551cd6e67351d194afc87c1d357510ad0344c",
    "certificate_chain_validation": {
        "can_sign": true,
        "usage_error": "",
        "valid": true,
        "validation_errors": [],
        "general_error": "",
        "main_valid": true,
        "alt_valid": true
    }
}
```
