# Castro AAC

[![Go Report Card](https://goreportcard.com/badge/github.com/Raggaer/castro)](https://goreportcard.com/report/github.com/Raggaer/castro)
[![lICENSE](https://img.shields.io/packagist/l/doctrine/orm.svg)](https://github.com/Raggaer/castro/blob/master/LICENSE)
[![Build status](https://ci.appveyor.com/api/projects/status/yhrx9l6jrbvxhw5p?svg=true)](https://ci.appveyor.com/project/Raggaer/castro)

High performance Open Tibia content management system written in **Go** using **Lua** for the scripting part.

Castro provides lua bindings. Using a pool of lua states. Each request gets a state from the pool. If there are no states available a new one is created and later saved on the pool.

## Documentation

Everything you might need [is here](https://docs.castroaac.org/). The official documentation site of Castro.

## Extensions

Castro ships with a very solid extension system. You can read more about it on the [documentation page](https://castroaac.org/docs/extensions) and grab your extensions on the [plugin list](https://plugins.castroaac.org).

## License

**Castro** is licensed under the **MIT** license.
