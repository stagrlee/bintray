[bintray](../../index.html)
# package-exists 

Checks if the package exists.

## SYNOPSIS

    rerun bintray:package-exists --user <> --apikey <> --org <> --package <> --repo <>

### OPTIONS

* [    --user <>: The bintray subject, aka username.](../../options/user/index.html)
* [    --apikey <>: The password used for REST authentication.](../../options/apikey/index.html)
* [    --org <>: The bintray organization.](../../options/org/index.html)
* [    --package <>: The package name.](../../options/package/index.html)
* [    --repo <>: The targeted repo.](../../options/repo/index.html)

## README



## TESTS

Use the `stubbs:test` command to to run test plans.

    rerun stubbs:test -m bintray -p package-exists

*Test plan sources*

* [package-exists-1](../../tests/package-exists-1.html)
  * it fails without a real test

## SCRIPT

To edit the command script for the bintray:package-exists command, 
use the `stubbs:edit`
command. It will open the command script in your shell EDITOR.

    rerun stubbs:edit -m bintray -c package-exists

*Script source*

* [script](script.html): `RERUN_MODULE_DIR/commands/package-exists/script`

## METADATA

* `NAME` = package-exists
* `DESCRIPTION` = "Checks if the package exists."
* `OPTIONS` = "user apikey org package repo"

----

*Generated by stubbs:docs Sun May 19 09:22:45 PDT 2013*

