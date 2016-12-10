# Meta
Meta project of sjtu-ai-go.

## Usage
1. Clone this project
2. Modify `.gitmodules` into `git://` or any other address you have write access to that repository, then run `git submodule sync`
3. `git submodule update --init --recursive`
4. Once a project was updated, use `git submodule foreach --recursive 'git pull origin master; git submodule update --init --recursive'` to propagate dependency, then try `git submodule foreach --recursive 'git commit -m "Bump dependency" && git push origin master'`
