# :package_name

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Build Status][ico-scrutinizer]][link-scrutinizer]
[![Build Status][ico-coverage]][link-coverage]


[![Build Status][ico-ndrx]][link-ndrx]

**Skeleton usage:** Do not fork this repository to create a real package, [download last release](https://github.com/ndrx-io/php-skeleton/archive/master.zip) and use the folder as base for your package/project.

Then replace ```:author_name``` ```:author_username``` ```:author_website``` ```:author_email``` ```:package_name``` ```:package_description``` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line.

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Install

Via Composer

``` bash
$ composer require ndrx-io/:package_name
```

## Usage

``` php
$skeleton = new \Ndrx\Skeleton\SkeletonClass();
echo $skeleton->echoPhrase('Hello, Ndrx!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email :author_email instead of using the issue tracker.

## Credits

- [:author_name][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/ndrx-io/:package_name.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/ndrx-io/:package_name/master.svg?style=flat-square
[ico-ndrx]: https://pbs.twimg.com/profile_images/585415130881642497/Qg4niE0o.png
[ico-scrutinizer]: https://scrutinizer-ci.com/g/ndrx-io/:package_name/badges/quality-score.png?b=master
[ico-coverage]: https://scrutinizer-ci.com/g/ndrx-io/:package_name/badges/coverage.png?b=master


[link-packagist]: https://packagist.org/packages/ndrx-io/:package_name
[link-travis]: https://travis-ci.org/ndrx-io/:package_name
[link-author]: https://github.com/:author_username
[link-contributors]: ../../contributors
[link-ndrx]: http://ndrx.io
[link-scrutinizer]: https://scrutinizer-ci.com/g/ndrx-io/:package_name/
[link-coverage]: https://scrutinizer-ci.com/g/ndrx-io/:package_name/
