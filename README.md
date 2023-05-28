# Relearn Foundry

Trying to keep up with the latest version of foundry.

## Foundry Installation

To install foundry on macOS, it's recommended to use `fondryup`. Use the
following command to install foundry:

```sh
curl -L https://foundry.paradigm.xyz | bash
```

Then run:

```sh
foundryup
```

You should see installation like below:

```
.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx

 ╔═╗ ╔═╗ ╦ ╦ ╔╗╔ ╔╦╗ ╦═╗ ╦ ╦         Portable and modular toolkit
 ╠╣  ║ ║ ║ ║ ║║║  ║║ ╠╦╝ ╚╦╝    for Ethereum Application Development
 ╚   ╚═╝ ╚═╝ ╝╚╝ ═╩╝ ╩╚═  ╩                 written in Rust.

.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx

Repo       : https://github.com/foundry-rs/
Book       : https://book.getfoundry.sh/
Chat       : https://t.me/foundry_rs/
Support    : https://t.me/foundry_support/
Contribute : https://github.com/orgs/foundry-rs/projects/2/

.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx.xOx

foundryup: installing foundry (version nightly, tag nightly-ad751b2f2ee1192d86624167fd5017d20cefd1d2)
foundryup: downloading latest forge, cast, anvil, and chisel
######################################################################### 100.0%
foundryup: downloading manpages
################################################################################################### 100.0%
foundryup: installed - forge 0.2.0 (ad751b2 2023-05-28T00:12:38.980432000Z)
foundryup: installed - cast 0.2.0 (ad751b2 2023-05-28T00:12:38.980432000Z)
foundryup: installed - anvil 0.1.0 (ad751b2 2023-05-28T00:12:56.008029000Z)
foundryup: installed - chisel 0.1.1 (ad751b2 2023-05-28T00:12:55.871105000Z)
foundryup: done!
```

## New Foundry Project

Use `forge` to initialize new project:

```sh
forge init refresh-foundry
```

The foundry project is not designed for monorepo, you may need to move `.github`
to root directory of your monorepo.
