# test-branch
Repository to test of branch

## Test senary
Branchs
- main
- develop
    - featureA
    - featureB

Objective
Using command `git merge branch-to-merge`.
Marge the branchs featureA end featureB, test end only after this
marge branch `develop` whith branch `main`

## Steps
- Create the branch `develop` based of the branch `main`
`$ git branch -b develop`

- Create the branchs `featureA` end `featureB`
`$ git branch -b featureA`
`$ git branch -b featureB`

- Do cheches in branchs `featureA` end `featureB`

- Active branch `develop`
`git checkout develop`

- Merge branchs `featureA` end `featureB`
`git merge featureA`
`git merge featureB`

create pull request...
