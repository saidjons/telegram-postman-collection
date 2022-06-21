# Telegram Bot API versions

This repository aims to store a schema for every version of the Telegram Bot API.

The goal is achieved by using [TGScraper](https://github.com/Sysbot-org/tgscraper). Old bot API schemas have been
extracted by using [The Wayback Machine](https://web.archive.org/web/*/https://core.telegram.org/bots/api).


## Versions list

| Version           | Description                                                                                               | Release date                                                                         | Custom                                                                       | Postman                           | OpenAPI                                                                        | Stubs                         |
|-------------------|-----------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|------------------------------------------------------------------------------|-----------------------------------|--------------------------------------------------------------------------------|-------------------------------|
| 6.1 **(current)** | Telegram Premium, public join requests, attachment menu.                                                  | [June 20, 2022](https://core.telegram.org/bots/api-changelog#june-20-2022)           | [JSON](files/custom/json/v610.json), [YAML](files/custom/yaml/v600.yaml)     | [JSON](files/postman/v610.json)   | [JSON](files/openapi/json/v610.json), [YAML](files/openapi/yaml/v610.yaml)     | [ZIP](files/stubs/v610.zip)   |
| 6.0               | Web Apps, default administrator rights.                                                                   | [April 16, 2022](https://core.telegram.org/bots/api-changelog#april-16-2022)         | [JSON](files/custom/json/v600.json), [YAML](files/custom/yaml/v600.yaml)     | [JSON](files/postman/v600.json)   | [JSON](files/openapi/json/v600.json), [YAML](files/openapi/yaml/v600.yaml)     | [ZIP](files/stubs/v600.zip)   |
| 5.7               | Video stickers.                                                                                           | [January 31, 2022](https://core.telegram.org/bots/api-changelog#january-31-2022)     | [JSON](files/custom/json/v570.json), [YAML](files/custom/yaml/v570.yaml)     | [JSON](files/postman/v570.json)   | [JSON](files/openapi/json/v570.json), [YAML](files/openapi/yaml/v570.yaml)     | [ZIP](files/stubs/v570.zip)   |
| 5.6               | Spoilers, send messages as protected content.                                                             | [December 30, 2021](https://core.telegram.org/bots/api-changelog#december-30-2021)   | [JSON](files/custom/json/v560.json), [YAML](files/custom/yaml/v560.yaml)     | [JSON](files/postman/v560.json)   | [JSON](files/openapi/json/v560.json), [YAML](files/openapi/yaml/v560.yaml)     | [ZIP](files/stubs/v560.zip)   |
| 5.5               | Start chats by join requests, protected content, anonymous channels.                                      | [December 7, 2021](https://core.telegram.org/bots/api-changelog#december-7-2021)     | [JSON](files/custom/json/v550.json), [YAML](files/custom/yaml/v550.yaml)     | [JSON](files/postman/v550.json)   | [JSON](files/openapi/json/v550.json), [YAML](files/openapi/yaml/v550.yaml)     | [ZIP](files/stubs/v550.zip)   |
| 5.4               | Chat join requests, choose_sticker chat action.                                                           | [November 5, 2021](https://core.telegram.org/bots/api-changelog#november-5-2021)     | [JSON](files/custom/json/v540.json), [YAML](files/custom/yaml/v540.yaml)     | [JSON](files/postman/v540.json)   | [JSON](files/openapi/json/v540.json), [YAML](files/openapi/yaml/v540.yaml)     | [ZIP](files/stubs/v540.zip)   |
| 5.3               | Scoped commands, ChatMember splitting.                                                                    | [June 25, 2021](https://core.telegram.org/bots/api-changelog#june-25-2021)           | [JSON](files/custom/json/v530.json), [YAML](files/custom/yaml/v530.yaml)     | [JSON](files/postman/v530.json)   | [JSON](files/openapi/json/v530.json), [YAML](files/openapi/yaml/v530.yaml)     | [ZIP](files/stubs/v530.zip)   |
| 5.2               | Payments 2.0, other minor changes.                                                                        | [April 26, 2021](https://core.telegram.org/bots/api-changelog#april-26-2021)         | [JSON](files/custom/json/v520.json), [YAML](files/custom/yaml/v520.yaml)     | [JSON](files/postman/v520.json)   | [JSON](files/openapi/json/v520.json), [YAML](files/openapi/yaml/v520.yaml)     | [ZIP](files/stubs/v520.zip)   |
| 5.1               | New Update type: ChatMemberUpdated. Improved chat invite links, voice chats support, other major changes. | [March 9, 2021](https://core.telegram.org/bots/api-changelog#march-9-2021)           | [JSON](files/custom/json/v510.json), [YAML](files/custom/yaml/v510.yaml)     | [JSON](files/postman/v510.json)   | [JSON](files/openapi/json/v510.json), [YAML](files/openapi/yaml/v510.yaml)     | [ZIP](files/stubs/v510.zip)   |
| 5.0               | Self-host Bot API, transfer bot ownership, other major changes.                                           | [November 4, 2020](https://core.telegram.org/bots/api-changelog#november-4-2020)     | [JSON](files/custom/json/v500.json), [YAML](files/custom/yaml/v500.yaml)     | [JSON](files/postman/v500.json)   | [JSON](files/openapi/json/v500.json), [YAML](files/openapi/yaml/v500.yaml)     | [ZIP](files/stubs/v500.zip)   |
| 4.9               | via_bot field in Message object, basketball support for dice.                                             | [June 4, 2020](https://core.telegram.org/bots/api-changelog#june-4-2020)             | [JSON](files/custom/json/v490.json), [YAML](files/custom/yaml/v490.yaml)     | [JSON](files/postman/v490.json)   | [JSON](files/openapi/json/v490.json), [YAML](files/openapi/yaml/v490.yaml)     | [ZIP](files/stubs/v490.zip)   |
| 4.8               | Dart support for dice, explanations for quizzes, automatically close poll.                                | [April 24, 2020](https://core.telegram.org/bots/api-changelog#april-24-2020)         | [JSON](files/custom/json/v480.json), [YAML](files/custom/yaml/v480.yaml)     | [JSON](files/postman/v480.json)   | [JSON](files/openapi/json/v480.json), [YAML](files/openapi/yaml/v480.yaml)     | [ZIP](files/stubs/v480.zip)   |
| 4.7               | Dice support, setMyCommands and getMyCommands, support for creating animated sticker packs.               | [March 30, 2020](https://core.telegram.org/bots/api-changelog#march-30-2020)         | [JSON](files/custom/json/v470.json), [YAML](files/custom/yaml/v470.yaml)     | [JSON](files/postman/v470.json)   | [JSON](files/openapi/json/v470.json), [YAML](files/openapi/yaml/v470.yaml)     | [ZIP](files/stubs/v470.zip)   |
| 4.6               | Polls 2.0, improved getMe.                                                                                | [January 23, 2020](https://core.telegram.org/bots/api-changelog#january-23-2020)     | [JSON](files/custom/json/v460.json), [YAML](files/custom/yaml/v460.yaml)     | [JSON](files/postman/v460.json)   | [JSON](files/openapi/json/v460.json), [YAML](files/openapi/yaml/v460.yaml)     | [ZIP](files/stubs/v460.zip)   |
| 4.5               | MarkdownV2 support, nested Message entities, file unique ID, custom administrator title.                  | [December 31, 2019](https://core.telegram.org/bots/api-changelog#december-31-2019)   | [JSON](files/custom/json/v450.json), [YAML](files/custom/yaml/v450.yaml)     | [JSON](files/postman/v450.json)   | [JSON](files/openapi/json/v450.json), [YAML](files/openapi/yaml/v450.yaml)     | [ZIP](files/stubs/v450.zip)   |
| 4.4               | Support for animated stickers and default chat permissions.                                               | [July 29, 2019](https://core.telegram.org/bots/api-changelog#july-29-2019)           | [JSON](files/custom/json/v440.json), [YAML](files/custom/yaml/v440.yaml)     | [JSON](files/postman/v440.json)   | [JSON](files/openapi/json/v440.json), [YAML](files/openapi/yaml/v440.yaml)     | [ZIP](files/stubs/v440.zip)   |
| 4.3               | Seamless Telegram Login, ReplyMarkup included in Message object.                                          | [May 31, 2019](https://core.telegram.org/bots/api-changelog#may-31-2019)             | [JSON](files/custom/json/v430.json), [YAML](files/custom/yaml/v430.yaml)     | [JSON](files/postman/v430.json)   | [JSON](files/openapi/json/v430.json), [YAML](files/openapi/yaml/v430.yaml)     | [ZIP](files/stubs/v430.zip)   |
| 4.2               | Added Poll support, pin messages in basic groups, other major changes.                                    | [April 14, 2019](https://core.telegram.org/bots/api-changelog#april-14-2019)         | [JSON](files/custom/json/v420.json), [YAML](files/custom/yaml/v420.yaml)     | [JSON](files/postman/v420.json)   | [JSON](files/openapi/json/v420.json), [YAML](files/openapi/yaml/v420.yaml)     | [ZIP](files/stubs/v420.zip)   |
| 4.1               | Minor changes for Telegram Passport.                                                                      | [August 27, 2018](https://core.telegram.org/bots/api-changelog#august-27-2018)       | [JSON](files/custom/json/v410.json), [YAML](files/custom/yaml/v410.yaml)     | [JSON](files/postman/v410.json)   | [JSON](files/openapi/json/v410.json), [YAML](files/openapi/yaml/v410.yaml)     | [ZIP](files/stubs/v410.zip)   |
| 4.0               | Telegram Passport, edit media content in messages, other major changes.                                   | [July 26, 2018](https://core.telegram.org/bots/api-changelog#july-26-2018)           | [JSON](files/custom/json/v400.json), [YAML](files/custom/yaml/v400.yaml)     | [JSON](files/postman/v400.json)   | [JSON](files/openapi/json/v400.json), [YAML](files/openapi/yaml/v400.yaml)     | [ZIP](files/stubs/v400.zip)   |
| 3.6               | Text formatting in captions, Login Widget support.                                                        | [February 13, 2018](https://core.telegram.org/bots/api-changelog#february-13-2018)   | [JSON](files/custom/json/v360.json), [YAML](files/custom/yaml/v360.yaml)     | [JSON](files/postman/v360.json)   | [JSON](files/openapi/json/v360.json), [YAML](files/openapi/yaml/v360.yaml)     | [ZIP](files/stubs/v360.zip)   |
| 3.5               | Media albums, message pinning in channel.                                                                 | [November 17, 2017](https://core.telegram.org/bots/api-changelog#november-17-2017)   | [JSON](files/custom/json/v350.json), [YAML](files/custom/yaml/v350.yaml)     | [JSON](files/postman/v350.json)   | [JSON](files/openapi/json/v350.json), [YAML](files/openapi/yaml/v350.yaml)     | [ZIP](files/stubs/v350.zip)   |
| 3.4               | Support for Live Location and group sticker sets management.                                              | [October 11, 2017](https://core.telegram.org/bots/api-changelog#october-11-2017)     | Not available.                                                               | Not available.                    | Not available.                                                                 | Not available.                |
| 3.3               | Support for creating mentions, other minor changes.                                                       | [August 23, 2017](https://core.telegram.org/bots/api-changelog#august-23-2017)       | [JSON](files/custom/json/v330.json), [YAML](files/custom/yaml/v330.yaml)     | [JSON](files/postman/v330.json)   | [JSON](files/openapi/json/v330.json), [YAML](files/openapi/yaml/v330.yaml)     | [ZIP](files/stubs/v330.zip)   |
| 3.2               | Support for sticker sets management.                                                                      | [July 21, 2017](https://core.telegram.org/bots/api-changelog#july-21-2017)           | [JSON](files/custom/json/v320.json), [YAML](files/custom/yaml/v320.yaml)     | [JSON](files/postman/v320.json)   | [JSON](files/openapi/json/v320.json), [YAML](files/openapi/yaml/v320.yaml)     | [ZIP](files/stubs/v320.zip)   |
| 3.1               | ChatMember permissions, temporary bans, support for pinning and unpinning messages.                       | [June 30, 2017](https://core.telegram.org/bots/api-changelog#june-30-2017)           | [JSON](files/custom/json/v310.json), [YAML](files/custom/yaml/v310.yaml)     | [JSON](files/postman/v310.json)   | [JSON](files/openapi/json/v310.json), [YAML](files/openapi/yaml/v310.yaml)     | [ZIP](files/stubs/v310.zip)   |
| 3.0               | Payment Platform, video messages, language code.                                                          | [May 18, 2017](https://core.telegram.org/bots/api-changelog#may-18-2017)             | [JSON](files/custom/json/v300.json), [YAML](files/custom/yaml/v300.yaml)     | [JSON](files/postman/v300.json)   | [JSON](files/openapi/json/v300.json), [YAML](files/openapi/yaml/v300.yaml)     | [ZIP](files/stubs/v300.zip)   |
| 2.3.1             | Webhook improvements.                                                                                     | [December 4, 2016](https://core.telegram.org/bots/api-changelog#december-4-2016)     | [JSON](files/custom/json/v231.json), [YAML](files/custom/yaml/v231.yaml)     | [JSON](files/postman/v231.json)   | [JSON](files/openapi/json/v231.json), [YAML](files/openapi/yaml/v231.yaml)     | [ZIP](files/stubs/v231.zip)   |
| 2.3               | Channel post updates, callback query cache, other changes.                                                | [November 21, 2016](https://core.telegram.org/bots/api-changelog#november-21-2016)   | [JSON](files/custom/json/v230.json), [YAML](files/custom/yaml/v230.yaml)     | [JSON](files/postman/v230.json)   | [JSON](files/openapi/json/v230.json), [YAML](files/openapi/yaml/v230.yaml)     | [ZIP](files/stubs/v230.zip)   |
| 2.2               | Gaming Platform, various changes.                                                                         | [October 3, 2016](https://core.telegram.org/bots/api-changelog#october-3-2016)       | [JSON](files/custom/json/v220.json), [YAML](files/custom/yaml/v220.yaml)     | [JSON](files/postman/v220.json)   | [JSON](files/openapi/json/v220.json), [YAML](files/openapi/yaml/v220.yaml)     | [ZIP](files/stubs/v220.zip)   |
| 2.1.1             | Added support for inline keyboards in groups.                                                             | [May 25, 2016](https://core.telegram.org/bots/api-changelog#may-25-2016)             | [JSON](files/custom/json/v211.json)\*, [YAML](files/custom/yaml/v211.yaml)\* | [JSON](files/postman/v211.json)\* | [JSON](files/openapi/json/v211.json)\*, [YAML](files/openapi/yaml/v211.yaml)\* | [ZIP](files/stubs/v211.zip)\* |
| 2.1               | More administration tools, support for edited messages and mentions.                                      | [May 22, 2016](https://core.telegram.org/bots/api-changelog#may-22-2016)             | [JSON](files/custom/json/v210.json), [YAML](files/custom/yaml/v210.yaml)     | [JSON](files/postman/v210.json)   | [JSON](files/openapi/json/v210.json), [YAML](files/openapi/yaml/v210.yaml)     | [ZIP](files/stubs/v210.zip)   |
| 2.0.2             | Message consistency for bot in groups and supergroups.                                                    | [May 12, 2016](https://core.telegram.org/bots/api-changelog#may-12-2016)             | Not available.                                                               | Not available.                    | Not available.                                                                 | Not available.                |
| 2.0.1             | Minor changes.                                                                                            | [May 6, 2016](https://core.telegram.org/bots/api-changelog#may-6-2016)               | Not available.                                                               | Not available.                    | Not available.                                                                 | Not available.                |
| 2.0               | Message editing, inline keyboards introduced, improved inline mode, basic administration tools.           | [April 9, 2016](https://core.telegram.org/bots/api-changelog#april-9-2016)           | [JSON](files/custom/json/v200.json), [YAML](files/custom/yaml/v200.yaml)     | [JSON](files/postman/v200.json)   | [JSON](files/openapi/json/v200.json), [YAML](files/openapi/yaml/v200.yaml)     | [ZIP](files/stubs/v200.zip)   |
| 1.8.3             | Support for sending silent messages.                                                                      | [February 20, 2016](https://core.telegram.org/bots/api-changelog#february-20-2016)   | [JSON](files/custom/json/v183.json), [YAML](files/custom/yaml/v183.yaml)     | [JSON](files/postman/v183.json)   | [JSON](files/openapi/json/v183.json), [YAML](files/openapi/yaml/v183.yaml)     | [ZIP](files/stubs/v183.zip)   |
| 1.8.2             | Added support for HTML-style formatting.                                                                  | [January 20, 2016](https://core.telegram.org/bots/api-changelog#january-20-2016)     | [JSON](files/custom/json/v182.json), [YAML](files/custom/yaml/v182.yaml)     | [JSON](files/postman/v182.json)   | [JSON](files/openapi/json/v182.json), [YAML](files/openapi/yaml/v182.yaml)     | [ZIP](files/stubs/v182.zip)   |
| 1.8.1             | Added ChosenInlineResult.                                                                                 | [January 14, 2016](https://core.telegram.org/bots/api-changelog#january-14-2016)     | Not available.                                                               | Not available.                    | Not available.                                                                 | Not available.                |
| 1.8               | Inline mode support.                                                                                      | [January 4, 2016](https://core.telegram.org/bots/api-changelog#january-4-2016)       | [JSON](files/custom/json/v180.json), [YAML](files/custom/yaml/v180.yaml)     | [JSON](files/postman/v180.json)   | [JSON](files/openapi/json/v180.json), [YAML](files/openapi/yaml/v180.yaml)     | [ZIP](files/stubs/v180.zip)   |
| 1.7               | Introduced supergroup support for bots.                                                                   | [November 2015](https://core.telegram.org/bots/api-changelog#november-2015)          | Not available.                                                               | Not available.                    | Not available.                                                                 | Not available.                |
| 1.6               | Introduced channel support for bots.                                                                      | [October 8, 2015](https://core.telegram.org/bots/api-changelog#october-8-2015)       | [JSON](files/custom/json/v160.json), [YAML](files/custom/yaml/v160.yaml)     | [JSON](files/postman/v160.json)   | [JSON](files/openapi/json/v160.json), [YAML](files/openapi/yaml/v160.yaml)     | [ZIP](files/stubs/v160.zip)   |
| 1.5               | Download files and media sent by users.                                                                   | [September 18, 2015](https://core.telegram.org/bots/api-changelog#september-18-2015) | [JSON](files/custom/json/v150.json), [YAML](files/custom/yaml/v150.yaml)     | [JSON](files/postman/v150.json)   | [JSON](files/openapi/json/v150.json), [YAML](files/openapi/yaml/v150.yaml)     | [ZIP](files/stubs/v150.zip)   |
| 1.4               | JSON requests, basic Markdown support.                                                                    | [September 7, 2015](https://core.telegram.org/bots/api-changelog#september-7-2015)   | [JSON](files/custom/json/v140.json), [YAML](files/custom/yaml/v140.yaml)     | [JSON](files/postman/v140.json)   | [JSON](files/openapi/json/v140.json), [YAML](files/openapi/yaml/v140.yaml)     | [ZIP](files/stubs/v140.zip)   |
| 1.3               | Support for self-signed certificates and webhook payload requests.                                        | [August 29, 2015](https://core.telegram.org/bots/api-changelog#august-29-2015)       | Not available.                                                               | Not available.                    | Not available.                                                                 | Not available.                |
| 1.2               | Voice messages.                                                                                           | [August 15, 2015](https://core.telegram.org/bots/api-changelog#august-15-2015)       | Not available.                                                               | Not available.                    | Not available.                                                                 | Not available.                |
| 1.1               | Minor changes.                                                                                            | [July 2015](https://core.telegram.org/bots/api-changelog#july-2015)                  | [JSON](files/custom/json/v110.json), [YAML](files/custom/yaml/v110.yaml)     | [JSON](files/postman/v110.json)   | [JSON](files/openapi/json/v110.json), [YAML](files/openapi/yaml/v110.yaml)     | [ZIP](files/stubs/v110.zip)   |
| 1.0               | First release.                                                                                            | [June 24, 2015](https://core.telegram.org/bots/api-changelog#june-24-2015)           | [JSON](files/custom/json/v100.json), [YAML](files/custom/yaml/v100.yaml)     | [JSON](files/postman/v100.json)   | [JSON](files/openapi/json/v100.json), [YAML](files/openapi/yaml/v100.yaml)     | [ZIP](files/stubs/v100.zip)   |

*Unchanged from previous version.

## Found a missing version?

Please, open an issue [here](https://github.com/sys-001/telegram-bot-api-versions/issues) providing the link and specifying the target version. It would help a lot!