This is an example of a respository which uses a github action place a Godot addon from a submodule-supporting repo in the addons folder.
The addon is updated at the end of every day, or when the "Update Addon" action is called manually.
Since this doesn't actually use submodules, it should support uploading to the Godot asset libarary.

The actual README.md file is copied from the addon repo.

> [!WARNING]
> You MUST give the github actions write access to your repo or this will always fail!
> -> This setting is in in Settings->Actions->General, at the bottom of the page
> Note: This step may fail if the target repo has no changes since the last run (which is ok)
