AEXT Exchange Developer Log
===

This is the log about developing AEXT Exchange. 

This is the close source business project.

![aext-20210606-0001.png](img/aext-20210606-0001.png) 

------

Revision: c0d43e713b495eb39d972dbbed84dca14474ca6c
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/27 下午 11:59:32
Message:
Add API: "/new/base64". Return image encode by base64.


Revision: 57885d8604424e9b771fb040da7edd3599244f87
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/27 下午 11:33:13
Message:
Add common Redis function for string value.
Add IP time lock for captcha.

Revision: 2273fc49d85e8f1cd96d1c3600a9ae2a7da02241
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/27 下午 08:05:23
Message:
Add API: "/new/image". Generate the captcha image.


Revision: 3c6c43bc9abdedd72d9f9a4ca9cbe0db6f7ab51b
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/27 下午 01:11:56
Message:
Add the Validation Exception handler to process BindingResult.


Revision: f92fc9daf4414e25a4c66fade0b1ea0b40291e15
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/27 上午 11:44:22
Message:
Add custom class-level validation for complex valid.


Revision: e789a6612e6a20f271f55e22fba9a67f4a919bce
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/26 下午 10:32:57
Message:
Add API: /password/modify. Send the mail for beginning reset password after login.


Revision: 1fea1fb7d9e552f22970bef7f3521408970e9b98
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/26 下午 09:13:05
Message:
Add API: "reactivate". Send activate email.


Revision: d35398eb9e059e7256928d6eadd581d567888f03
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/26 下午 06:46:51
Message:
Add the delay time for member register according IP.


Revision: e109e8973c5c23cb93ac53e9aad084edce15a043
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/26 下午 04:28:50
Message:
Add IP utils.


Revision: 13fca6d48161c900c9f995e7bb7ecbd49d95edfe
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/26 下午 02:29:06
Message:
Add API: verify. It can use for find password or others that need verify.


Revision: 41094ad02e7ce2a551c1fd363e2df32e8103049f
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/26 上午 10:59:56
Message:
Add API: activate. Member can activate by email.
Add clean redis at dev mode.

Revision: a3854fe5ce277f965051ab6941bc88464a49f920
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/25 下午 10:52:59
Message:
Add initial data of database.


Revision: 3be8556f01275ba1d6b039932f8846e09f30c33d
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/25 下午 05:17:01
Message:
Add update function to MemberService.


Revision: be2e40f8146ac4d62d136e87fd3225d3a209af5f
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/25 下午 04:33:47
Message:
Fix the eclipse worried 'is an unknown property. Did you mean'.
Add owner properties.

Revision: 6093bbaa64835df48dcfb32e8df4e861663df8e8
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/25 下午 04:30:25
Message:
Add service of role.
Improve config for embedded Redis.

Revision: 7656e2bf41da4cf22840bc0f9f1c47f3aa0188be
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/24 下午 04:59:09
Message:
Improve API: "/logout" to support JWT logout with Redis.
Add short SHA2 function.

Revision: 8e111085a599116540396b315fdf5568052bcbf9
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/24 下午 02:02:07
Message:
Add the clean database script for dev profile.


Revision: f837b453f8be7e62674b78e6ebfd6dada6351565
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/24 下午 01:16:45
Message:
Add the prepare environment test function.


Revision: 21cfdcbcd2c34f42e522e217e28a40a69b849bd5
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/24 上午 10:26:27
Message:
Add the read permissions.


Revision: 1d701f45ed500e05c67aee124af149369188f0b9
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/19 下午 09:39:16
Message:
Add the new implement of PermissionService.


Revision: f31b7fa8661b3d5009d769c2daf82b70e04135dc
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/19 下午 06:25:38
Message:
Improve project architecture.


Revision: 3867a1dbe031ea96cbb7a1c347828e1962713806
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/19 下午 05:25:55
Message:
Add the OV that is new type of class for response.


Revision: 1d222766bee46f5052e002653a4c0a0ffe69b610
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/19 下午 04:01:17
Message:
Remove QueryDSL.


Revision: d48f83d41acb1febfa426d142ee298a077ae5abe
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/19 下午 03:23:11
Message:
Add the JPA method equal JSQL.


Revision: b31d6afe1189757106258bfac4d8ba06d4c25627
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/19 下午 12:46:06
Message:
Add Permission repository.
Remove QueryDSL because of low active community.

Revision: 7caad41c6b1ee3f35ec4799aa6d5d6a170c5e470
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/17 下午 07:07:41
Message:
Add authentication architecture.


Revision: 8a957978823e911bd357a52b936206a1bcffaafc
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/15 下午 12:30:51
Message:
The basic JWT integrate with spring security.


Revision: 8d8f41ae613f697320d8195853c148d05dd97340
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/14 下午 09:47:38
Message:
Add API: "/logout" that log out the member.


Revision: a3aefdf5118a4a59be8ee6002c07b6375db679ef
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/14 下午 06:55:21
Message:
Add the simple version for session login.


Revision: a71ce91af49d27b080854304c9af02cf2a541203
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/14 下午 12:36:32
Message:
Insert mock member at application startup.


Revision: 18ca3a8ff9dc9ea28a90c16eb53057bfc0905c38
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/13 下午 04:41:24
Message:
Add member status.


Revision: 3a452f5c97a12d875600198c0cf5ab9924eba24a
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/13 下午 04:25:14
Message:
Remove setter in enum.


Revision: 7aff01774d0afc4910445e199e15622a735bb3a7
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/13 下午 03:57:02
Message:
Add generic entity converter for EnumSet type of CommonStatus.


Revision: a0f5593adf1ee6d34934082ad66df091c70a35bb
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/13 下午 03:46:57
Message:
Add generic entity converter for EnumSet type of MemberLevelEnum.


Revision: 5a42c46ec86767d4c983ce70b816a2150507d90c
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/12 下午 11:39:45
Message:
Add multi language for email using thymeleaf.


Revision: c345e2559b8b5ecf6b538cff8a7ce7ffebef6fef
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/12 下午 07:20:26
Message:
Completed API: "/core-service/api/v1/member/register/email".


Revision: 230688758bfa39b5445167e30f1462ca9551191c
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/12 下午 05:01:48
Message:
Upgrade security.


Revision: 4e8454ba87730d76975fe5950b8a74d5087ad48b
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/12 下午 04:39:06
Message:
Integrate BCryptPasswordEncoder.


Revision: 4cb57b7ec726e270b1b407fcb135d985bbe61fe0
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/12 下午 04:32:41
Message:
Join spring security.


Revision: 43194849d4fbc614d91285e091288eb1b68fa694
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/12 下午 02:09:08
Message:
Add completed unit test, test runtime and dev runtime solution for embedded Redis.


Revision: 1501ab05c640f8e6c1844e46970fe2861c8260d1
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/12 上午 11:26:06
Message:
Improve exception.


Revision: 0c596c10252fc4ce9b156f1efe6be74e483e8145
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/11 下午 09:13:03
Message:
Add logback config with springboot.


Revision: 8cf9954d641b1f0054831a38dc594eddb512ea35
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/11 下午 07:32:53
Message:
Rename payload.


Revision: 08cf18e34e8d9258026353754ddf4f8c956c07ea
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/11 下午 07:15:25
Message:
Add builder for BindingResult data.


Revision: dfa0a71070129d0ea5f7ea16e03690274b5525b3
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/9 下午 01:42:16
Message:
Using StringRedisTemplate to fix the garbled text in DB.


Revision: 6601c7555528f538934e9a46bec8234649941b82
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/9 上午 11:03:53
Message:
Completed API "/v1/member/send/guest/email/verify" that can send the email include verify code.


Revision: 21cd375cb4ed983179f2b2c9d53de12b66ddb0cd
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/9 上午 08:34:25
Message:
Add the content builder for email.


Revision: 55f89db0220be5788de3413051576972d292aff3
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/8 下午 02:24:35
Message:
Add the builder for content of email.


Revision: 547747a57b9cd8dfb75c8ee4dc0c78ca79c644f5
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/7 下午 07:34:13
Message:
Add the IoC for JavaMailSender.


Revision: 94a05be4d01e2d5f9cecb655234fd8b7832380b4
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 10:47:03
Message:
Add send email service.


Revision: dd778465b889d5a90c1318343e3bbea73eb0984e
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 10:28:25
Message:
Improve response flow.


Revision: cdc495134ce50a07ea57a536023941edf3d2a273
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 10:14:01
Message:
Improve response ability.


Revision: 87da23dacd7ea208d3cd15e60a42ca2fba0a3096
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 09:07:09
Message:
Change name to 256.


Revision: 8275fee36aebea918a4a10f3e04e4cb11eb14baf
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 09:05:34
Message:
Add SHA2 for cryptography.


Revision: 292512414417a6832c926359b1580cc9a22eafeb
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 08:16:36
Message:
Add Value Validate for email, username, password and unit test.


Revision: d349af5f3f7e6a6a171c266b4b756d9f012a597e
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 07:47:52
Message:
Add find member by user name.


Revision: 9faeb7d99f8a78dd2108e2fa68de5fadfcc7e25a
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 07:16:29
Message:
Import i18n language document.


Revision: 30adeb9b2f09d5091af85aca413d3e23c18ca09b
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 07:15:08
Message:
Using "Optional" for query result.


Revision: ab63ad8823b6c912f1b3cb64f044aac623702cbb
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 07:03:23
Message:
Add find member by email.


Revision: bdd7891698a93848d5d25473676152e08e46473e
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 06:27:29
Message:
Fix build.gradle in the sub module.


Revision: 63f8349dd4de128ead74951e4f10d14d30e9a856
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 05:14:39
Message:
Add the LocaleMessageSourceService that make multi language more easy.


Revision: a75398c9c21b433de853dc34a6015823e87f468a
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 05:02:51
Message:
Add check user name is exist that support multi language.


Revision: c232d9aeccdbe43b3987022bbf3032a8c9b4fd10
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 04:28:11
Message:
Add Main project support @autowired with JPA.


Revision: 379796f7fd88afaf6ae8245a7cc2f1e77ab982fb
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 03:27:13
Message:
Add Check member's email exist.
Add the assertThrows lambda or classic test with Junit 5.

Revision: 8f27fddbf33ec05c3d7bf4c7e663f6873fb6fd8c
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 下午 02:13:10
Message:
Junit 5 support test of springboot library module with H2 database.


Revision: c67bab07276db36f53fe69e5e0a441a3f07352c3
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/6 上午 10:34:00
Message:
Add the @autowired work template.


Revision: 33b79a514cb69496434ee3a19ccc87c79ae03650
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/5 下午 10:59:13
Message:
Add custom enum and improve build.


Revision: 5b16051e4f371735e2c04dbc4acca459a04e6f44
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/5 下午 10:53:17
Message:
Fix unit test and improve build file.


Revision: afbbf64bb5c09fe7b617241250fd06db0f50e3df
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/5 下午 02:52:06
Message:
Add multi language message.


Revision: 32d9f4ac2b076c41bb84866617a5300d1a6fa8d8
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/5 下午 02:30:38
Message:
Add internationalization of REST.


Revision: a143444c5c1f0764568eac635be9cbe79917b2ec
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/5 下午 01:01:59
Message:
Add the return message show errors.


Revision: e2e1665288e03b6e9eb89f6898d8712a852ca0e4
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/5 上午 11:53:31
Message:
Add multi language and payload of register by email.


Revision: 0205c584846e871398491460e6e8b3bc6eebbb92
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/5 上午 09:51:41
Message:
Add the base controller.


Revision: b4ec89fa4a2aabcf99aaad29719e7c7f240b5862
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/5 上午 09:36:00
Message:
Add MessageResponse for common return message.


Revision: ee5c28f0f0f597f0b6d1e64fa1a7a40fc58ed15c
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/4 下午 11:39:43
Message:
Add new empty project core-base for shared code base.


Revision: 4999de2353dd3c93ab43e5dbe609a67ec23f87f4
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/4 下午 11:38:47
Message:
Add Eureka server.


Revision: 86ddb459ad06a2394ab3dd044779e5f0187e96c5
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/4 下午 10:23:07
Message:
Add the new empty project for service discover and registration.


Revision: 250997e5c8114d8331256d620d17259f65ad5d1f
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/4 下午 10:22:11
Message:
Move core-service to backend.

Revision: 3f7fa9680061ef97d7f27e9bebf893e6aade1a51
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 2021/6/4 下午 10:04:10
Message:
Add the new project template.
