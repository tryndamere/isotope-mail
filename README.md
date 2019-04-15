# <img src="doc/isotope-logo-h-800.png" alt="Isotope Mail Client" />
 [![GitHub license](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/manusa/isotope-mail/blob/master/LICENSE) [![Build Status](https://travis-ci.org/manusa/isotope-mail.svg?branch=master)](https://travis-ci.org/manusa/isotope-mail) [![Code coverage](https://sonarcloud.io/api/project_badges/measure?project=manusa_isotope-mail&metric=coverage)](https://sonarcloud.io/component_measures?id=manusa_isotope-mail&metric=coverage) [![e2e tests](https://img.shields.io/travis/manusa/isotope-mail-e2e-tests.svg?label=e2e+tests)](https://travis-ci.org/manusa/isotope-mail-e2e-test) [![BrowserStack Status](https://www.browserstack.com/automate/badge.svg?badge_key=bXJrK3psdDRjUjBnZnhYZUF1ZERPbjhvQ1UrUnZpUE9lc2VNMkZaSERPRT0tLTIzNSt0KzhSTWRuZ0kvdkk1azJ0M0E9PQ==--e47df33166d4fa41158b8148af5e6f4430294a96)](https://www.browserstack.com/automate/public-build/bXJrK3psdDRjUjBnZnhYZUF1ZERPbjhvQ1UrUnZpUE9lc2VNMkZaSERPRT0tLTIzNSt0KzhSTWRuZ0kvdkk1azJ0M0E9PQ==--e47df33166d4fa41158b8148af5e6f4430294a96)

Microservice based webmail client built with ReactJS and Spring.

## Introduction

This webmail client is still in a very early stage, use at your own risk.

## TL;DR

If you just want to check out the current status of the project you can deploy the application
using the example traefik docker-compose.

Just run the following commands:

```
git clone https://github.com/manusa/isotope-mail.git
cd isotope-mail/docker/traefik
docker-compose pull && docker-compose up --force-recreate
```

Point your browser to [localhost](http://localhost) and login using the credentials of your mailserver.

<p>
  <img src="doc/tldr-isotope-deploy.gif" />
</p>

## Demo

You can see the latest snapshot version in action at: [isotope.marcnuri.com](https://isotope.marcnuri.com/login?serverHost=isotope&user=isotope&smtpPort=25&smtpSsl=false)

<p>
  <img src="doc/isotope-demo-login.gif" />
</p>

Use the following credentials:
 - Host: isotope
 - User: isotope
 - Password: demo

You can send e-mails to the demo account (isotope@isotope) by setting the SMTP server advanced settings:
 - Port: 25
 - SMTP SSL: false


## License

Isotope is [Apache 2.0 Licensed](./LICENSE).

## Acknowledgements

Isotope Mail team wants to recognize the following third parties for providing software,
support or services free of charge.

<img width=200 src="https://p14.zdusercontent.com/attachment/1015988/jnfTAsRFuKVzfvJMDJ8Ui45p8?token=eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..H0_YyxaE762GtXQvUnHoYw.R3tCI87tR-lehrK_zjT7GmEI--69EORCPWqTPY_iVa2Pt7468NrQBRAvoO5k1-H0W5YJGw45Fnz6ArGGOX796PWiCdTujuUv0_OTnRKnXU1Zjw3ytoLLFdZH1NTOxAvJUqt8RA3-Dj3mKJ-IGy7l-oqxN5zDXppNQA5xumK9uYu6VNp2JzjMg1ZnPzcOxub5jy7dqMmsxSN9mzpRgjjsNBUKI8a9I4jVzDm13tPLBjKl2bRdxVS14IapUYBpW8NRDrhw8f4mfYYtKR8CSFlCNiFkKtZd-CpZYGLgH7Y23CU.RqsF1R4_vpfkA7VhBRgsZQ" />

Thanks to [BrowserStack](https://www.browserstack.com) for providing a free open source account
to use their products for testing in real devices and browsers.
