![Tensor extension for windows](https://user-images.githubusercontent.com/38932580/210127590-fe13f65e-5e80-474b-bff7-6d487d490e18.png)
<br/>
[![Stargazers][stars-shield]][stars-url]
[![Forks][forks-shield]][forks-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
<br/>
<br/>
<a href="https://www.buymeacoffee.com/takielias" target="_blank"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="takielias" /></a>
<br/>
<br/>

Tensor Extension for Windows (8.1, 10, 11)

### Available PHP Versions

- PHP 7.4 (NTS)
- PHP 8.0 (TS,NTS)
- PHP 8.1 (TS,NTS)
- PHP 8.2 (TS,NTS)

## Usage

We usually use TS (Thread Safe) version of PHP. Please go through the article [here](https://stackoverflow.com/a/3983918) before using the TS/NTS version of this extension.

First download **libopenblas.dll** and the specific version of the extension  **php_tensor.dll**

Put the ```libopenblas.dll``` in the root directory of PHP.

![image](https://user-images.githubusercontent.com/38932580/187570817-77143f87-4c4f-4284-838e-f369745eaae0.png)

Now put the ```php_tensor.dll``` in the ext directory.

![image](https://user-images.githubusercontent.com/38932580/210128297-370521a5-69da-4d6f-a52a-73cd1437e9ae.png)

Now open the php.ini file and enable the tensor extension. 

![image](https://user-images.githubusercontent.com/38932580/210128348-e1992911-3393-4ba7-aece-92de3ce5c2dd.png)

```shell
extension=tensor
```

Now restart your server (Nginx/Apache) & PC. Open the command prompt & run the command below to verify the extension. 

```shell
php -m | grep tensor
```

![image](https://user-images.githubusercontent.com/38932580/210128424-a02e02d6-0c58-4dce-8345-f9a93cf13562.png)

If you get the output as ```tensor```, that means it's **DONE**

<!-- CONTACT -->

## Contact

Taki Elias - [@takiele](https://twitter.com/takiele) - [https://ebuz.xyz](https://ebuz.xyz) - taki.elias@gmail.com

## Support on Buy Me A Coffee

Hey dude! Help me out for a cup of ☕!

<a href="https://www.buymeacoffee.com/takielias" target="_blank">
<img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="takielias" /></a>

<br><br>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[forks-shield]: https://img.shields.io/github/forks/takielias/php-tensor-for-windows.svg?style=flat-square

[forks-url]: https://github.com/takielias/php-tensor-for-windows/network/members

[stars-shield]: https://img.shields.io/github/stars/takielias/php-tensor-for-windows.svg?style=flat-square

[stars-url]: https://github.com/takielias/php-tensor-for-windows/stargazers

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555

[linkedin-url]: https://linkedin.com/in/takielias

[link-author]: https://github.com/takielias
