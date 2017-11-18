# Sensu Plugin Skeleton

All the files you'll need to start your own plugin written in Ruby [for Sensu](https://github.com/sensu/sensu), the monitoring framework.

## Useful to Me?

* Copy the files in this repository if you want to write a Ruby plugin following best practices of layout and structure
* To write the actual functionality, you'll need to import [Sensu Plugin gem](https://github.com/sensu-plugins/sensu-plugin)
* If you'd prefer writing in Python, use the [Python Plugin library](https://github.com/sensu-plugins/sensu-plugin-python)
* Regardless of the chosen language, prepare the plugin to be released as a Ruby gem for optimal portability (example: [MongoDB has Ruby and Python code](https://github.com/sensu-plugins/sensu-plugins-mongodb/tree/master/bin))

## Checklist

To release your own plugin, complete the following:

- [ ] Double check that another plugin doesn't already do what you need by [searching the Sensu Plugins organization](https://github.com/sensu-plugins)
- [ ] Copy the files here into your own repository following the naming convention of `sensu-plugins-$FOO`
- [ ] Delete or move this file and rename `README-skel.md` to `README.md`
- [ ] Write your own checks, handlers or mutators using the plugin library of your choice
- [ ] Push them to your own GitHub repository
- [ ] Release them as a Ruby gem for optimal portability within the Sensu 1.x framework
- [ ] Ask for feedback from your peers by sharing it on in the #contributing channel on [Sensu Community Slack](http://slack.sensu.io)
- [ ] When you're ready to share further, offer to share it with broader community [by transferring it to Sensu Plugins organization](https://github.com/sensu-plugins/community/blob/master/TRANSFERRING_REPOS.md)
- [ ] If you end up loving maintaining your plugin, [volunteer to be an org maintainer](https://github.com/sensu-plugins/community#how-you-can-help)
