[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)

# Camunda Modeler element templates for Onify

Element templates allow you to create pre-defined configurations for BPMN elements such as service and user tasks. Once applied via the properties panel they provide configured custom inputs to the user. For more information, see https://docs.camunda.io/docs/components/modeler/desktop-modeler/element-templates/about-templates/.

This repo contains templates customized for Onify. Please feel free to use and/or contribute.

## Requirements

* [Camunda Modeler 5.x](https://camunda.com/download/modeler/)

## Setup

Copy `./onify-templates/*` to Camunda Modeler element templates folder (`./resources/element-templates`). 

> Note: You need to restart Camunda Modeler if you update the templates.

## Limitations

Here are some limitations for the Camunda Modeler elements templates.

* Does not support variables where `Assignment type` is `List` (script is used instead)
* Does not support variables where `Assignment type` is `Map` (script is used instead)

## Support

* Community/forum: https://support.onify.co/discuss
* Documentation: https://support.onify.co/docs
* Support and SLA: https://support.onify.co/docs/get-support

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.