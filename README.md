# Awesome CUE

A curated list of awesome [CUE](https://cuelang.org/) projects, libraries, tools and resources.

## Integrations

Build Tools

* [rules_cue](https://github.com/tnarg/rules_cue) - CUE rules for Bazel.

CICD

* [setup-cue](https://github.com/cue-lang/setup-cue) - GitHub actions workflow to install a specific version of CUE on your runner.

Configuration Management

* [terraform-provider-cue](https://github.com/xinau/terraform-provider-cue) - Terraform provider for interacting with CUE.

Editor

* [astexplorer-cue](https://github.com/brandonbloom/astexplorer-cue) - Ast Explorer support for CUE.
* [cue-mode](https://github.com/jdbaldry/cue-mode) -  Emacs major mode for CUE.
* [cue-mode](https://github.com/russell/cue-mode) - Provides Emacs font-lock, indentation, and some useful functions for the CUE data validation language.
* [intellij-cue](https://github.com/monogon-dev/intellij-cue) - IntelliJ support for the CUE language.
* [tree-sitter-cue](https://github.com/eonpatapon/tree-sitter-cue) -  Cue grammar for tree-sitter.
* [vscode-cue](https://github.com/cue-sh/vscode-cue) - CUE language support for Visual Studio Code.
* [vim-cue](https://github.com/jjo/vim-cue) - CUE syntax highlighting plugin for VIM.

Templates

* [cue-vscode-starter](https://github.com/golem-ai/cue-vscode-starter) - A VS Code Remote Containers project/environment made for CUE

## Projects

CUE

* [CUE Playground](https://cuelang.org/play/#cue@export@cue) - Interactive playground for CUE
* [cuemod](https://github.com/octohelm/cuemod) - Dependency management for CUE without committing cue.mod.
* [Cuetils](https://github.com/hofstadter-io/cuetils) - CLI and library for diff, patch, and ETL operations on CUE
* [unity](https://github.com/cue-lang/unity) - run experiments/regression tests on CUE modules.

Kubernetes

* [cuebe](https://github.com/loft-orbital/cuebe) - Kubernetes release manager powered by CUE.
* [cuek8s](https://github.com/slewiskelly/cuek8s) - An experimental environment for a CUE based approach to Kubernetes manifest management. 
* [cuelm](https://github.com/hofstadter-io/cuelm) - Pure CUE implementation of Helm Kubernetes package manager.
* [kubevela](https://github.com/oam-dev/kubevela) - KubeVela is a modern application delivery platform.

Others

* [cute](https://github.com/yujinyan/cute) -  A cue-lang utility.
* [Dagger](https://dagger.io/) - A portable devkit for CICD
* [Hofstadter](https://www.hofstadter.io/) - High Code™ - for higher velocity development.
* [injecuet](https://github.com/aereal/injecuet) - The injecuet injects concrete values and emits new CUE document.
* [kuegen](https://github.com/errordeveloper/kuegen) - kuegen is a simple config generator based on CUE.
* [slo-cue](https://github.com/cbrgm/slo-cue) - Generate Prometheus alerting & recording rules for SLOs using CUE.
* [stax](https://github.com/cue-sh/stax) - Go-based CLI for managing CloudFormation stacks written in Cue
* [Thema](https://github.com/grafana/thema) - A CUE-based framework for portable, evolvable schema.

<!-- * [c8s](https://github.com/hofstadter-io/c8s) - Cuelang powered Kubernetes package manager. -->
<!-- * [systool](https://github.com/hdonnay/systool) - A proof of concept for using cue to generate shell scripts. -->

## Schemas

CICD

* [ghacue](https://github.com/hofstadter-io/ghacue) - GitHub Actions schema in CUE

<!-- * [cue-ansible](https://github.com/adieu/cue-ansible) - Write Ansible Playbooks in CUE -->

Configuration Management

* [cfn-cue](https://github.com/cue-sh/cfn-cue) - Generated CUE schema from CloudFormation Resource Specification.
* [cue_terraform](https://github.com/tnarg/cue_terraform) -  CUE definitions for terraform providers.

Security

* [tmdl](https://github.com/abhaybhargav/tmdl) - Threat Model Definition Language using a declarative syntax with CUE. 

## Resources

References

* [CUE Documentation](https://cuelang.org/docs/) - Official documentation about what CUE is and how to use it.
* [CUE Language Specification](https://cuelang.org/docs/references/spec/) - A reference manual for the CUE data constraint language.
* [Go Documentation](https://pkg.go.dev/cuelang.org/go/cue) - Go documentation of the main API for CUE evaluation.
* [Go StdLib Documenation](https://pkg.go.dev/cuelang.org/go/pkg) - Go documentation of the CUE standard packages. 
* [Logic of CUE](https://cuelang.org/docs/concepts/logic/) - Page explaining the core concept on which almost everything in CUE depends

Tutorials/Examples

* [CUE Documentation Tutorials](https://cuelang.org/docs/tutorials/) - CUE tutorials provided as part of the official documentation.
* [Cuetorials](https://cuetorials.com/) - Tutorial site to learn more about CUE by Hofstadter, Inc.
* [CUE for Network Configurations](https://github.com/networkop/cue-networking) - Example of using CUE to model baremetal network configurations.
* [GitHub Actions Example](https://github.com/cue-lang/github-actions-example) -  A simple, worked example of using CUE to manage Github Actions.
* [Kubernetes Tutorial](https://github.com/cue-lang/cue/blob/v0.4.1/doc/tutorial/kubernetes/README.md) - How to convert Kubernetes configuration files for a collection of microservices.

<!-- * [cue-examples](https://github.com/hofstadter-io/cue-examples) - Random examples demonstrating cuelang -->
<!-- * [automata](https://github.com/uhthomas/automata) - Monorepo for Starjunk and subsidiaries -->

Articles

* [How CUE Wins](https://blog.cedriccharly.com/post/20210523-how-cue-wins/)
* [Observability-kit: Adventures of using CUE at scale](https://engineering.mercari.com/en/blog/entry/20220122-adventures-of-using-cue-at-scale/) 
<!-- * [The Configuration Complexity Curse](https://blog.cedriccharly.com/post/20191109-the-configuration-complexity-curse/) -->
<!-- * [Automating the CUE workflow with Tilt](https://garethr.dev/2019/04/automating-the-cue-workflow-with-tilt/) -->
<!-- * [Testing Cue Configuration with Open Policy Agent](https://garethr.dev/2019/04/testing-cue-configuration-with-open-policy-agent/) -->
<!-- * [Configuring Kubernetes with CUE](https://garethr.dev/2019/04/configuring-kubernetes-with-cue/) -->
<!-- * [Validating Cue Kubernetes Configuration with Kubeval](https://garethr.dev/2019/04/validating-cue-kubernetes-configuration-with-kubeval/) -->


Videos

* [Contributing to CUE](https://www.youtube.com/watch?v=_vxoYVYbwf8)
* [CUE: a data constraint language and shoo-in for Go. Marcel van Lohuizen, Google.](https://www.youtube.com/watch?v=b3fhA12KS48)
* [CUE Town Hall #1](https://www.youtube.com/watch?v=Qp1F4AoSmxc)
* [GopherCon Europe 2020: Marcel van Lohuizen - Better APIs with Shareable Validation Logic](https://www.youtube.com/watch?v=IRNluM2B4p8)
* [Hands-on Introduction to CUE | Rawkode Live](https://www.youtube.com/watch?v=fR_yApIf6jU)
* [Large-Scale Engineering of Configuration with Unification (Marcel van Lohuizen)](https://www.youtube.com/watch?v=jSRXobu1jHk)
* [TGI Kubernetes 098: CUE templating language](https://www.youtube.com/watch?v=pyfU_ne-kOc)
* [Using CUE with GitHub Actions](https://www.youtube.com/watch?v=Ey3ca0K2h2U)

Podcasts

* [CUE: Configuration superpowers for everyone](https://changelog.com/gotime/163)

<!-- * [Scuemata: A Framework for Evolvable, Composable Data Schema (Sam Boyer)](https://www.youtube.com/watch?v=PpoS_ThntEM) -->

## Community

Community Sites

* [GitHub Discussion](github.com/cue-lang/cue/discussions) - GitHub Discussions to ask questions and discuss CUE.
* [Slack](https://cuelang.slack.com) - Slack organization to chat with other CUE enthusiasts.
* [Twitter](https://twitter.com/cue_lang) - Official Twitter Account to follow for announcements.
* [Youtube](https://www.youtube.com/channel/UCZ0I6tZzFxN15H2SaclJA9A) - CUE community Youtube Channel

## Other

* [awesome-cue-zh](https://github.com/chai2010/awesome-cue-zh) - CUE Resource Selection - Chinese Version
