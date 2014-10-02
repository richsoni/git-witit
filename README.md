#Git Up, Git Out

```git commit``` and ```git init``` are two of the slickest sounding commands the program offers.
Of all the 155 commands git offers (in version 2.2.1), there are only 5 that rhyme with git (commit, cvsexportcommit, init, verify-commit, mailsplit).
In that set, commit and init are the only two commonly used frequently.

Git is an easy word to find rhymes, and it is a share there are not more rhyming commands.
Git WitIt provides 27 commands proxies that rhyme with git, making a workflow more pleasurable.

# Take Notes On How I Grep't

<div class='col-xs-12 card container grid'>
  <table class='flush col-xs-12 col-sm-6'>
    <tbody>
      <tr> <td><code>admit</code></td>  <td>merge</td>       </tr>
      <tr> <td><code>aquit</code></td>  <td>blame</td>       </tr>
      <tr> <td><code>befit</code></td>  <td>cherry-pick</td> </tr>
      <tr> <td><code>bit</code></td>    <td>grep</td>        </tr>
      <tr> <td><code>chit</code></td>   <td>shortlog</td>    </tr>
      <tr> <td><code>emit</code></td>   <td>push</td>        </tr>
      <tr> <td><code>fit</code></td>    <td>rerere</td>      </tr>
      <tr> <td><code>flit</code></td>   <td>stash</td>       </tr>
      <tr> <td><code>it</code></td>     <td>checkout</td>    </tr>
      <tr> <td><code>kit</code></td>    <td>config</td>      </tr>
      <tr> <td><code>knit</code></td>   <td>rebase</td>      </tr>
      <tr> <td><code>legit</code></td>  <td>pull</td>        </tr>
      <tr> <td><code>mitt</code></td>   <td>fetch</td>  </tr>
      <tr> <td><code>nit</code></td>    <td>prune</td>  </tr>
      <tr> <td><code>omit</code></td>   <td>rm</td>     </tr>
      <tr> <td><code>permit</code></td> <td>add</td>    </tr>
      <tr> <td><code>pit</code></td>    <td>bisect</td> </tr>
      <tr> <td><code>refit</code></td>  <td>clone</td>  </tr>
      <tr> <td><code>remit</code></td>  <td>diff</td>   </tr>
      <tr> <td><code>shit</code></td>   <td>revert</td> </tr>
      <tr> <td><code>sit</code></td>    <td>tag</td>    </tr>
      <tr> <td><code>skit</code></td>   <td>log</td>    </tr>
      <tr> <td><code>split</code></td>  <td>branch</td> </tr>
      <tr> <td><code>sprit</code></td>  <td>mv</td>     </tr>
      <tr> <td><code>unfit</code></td>  <td>reset</td>  </tr>
      <tr> <td><code>witit</code></td>  <td>status</td> </tr>
      <tr> <td><code>writ</code></td>   <td>reflog</td> </tr>
    </tbody>
  </table>
</div>

<div class='cols-xs-12 image block' style='overflow:hidden'>
  <div class='col-xs-12 col-md-6' style='clear:both;margin-bottom:1em' >
    <img class='img-responsive' style='float:left' src='/images/blog/drenboi.png' />
    <div class='caption'>
    </div>
  </div>
</div>

### ...Go Ahead And Marinate On That For A Minute


#Installation

Here is the quick way to Git WitIt.

```
# put the two and two together
$ cd path/to/a/folder/you/choose
$ wget tk
$ git config --global --add include.path `pwd`/gitwitit.inc
```

Enjoy using Git WitIt, you should be done.

Test it by typing ```git witit``` in a git repository.

## The Details

The above steps should seamlessly install git witit, but some environments may need customization.
Here are the dirty details, for exotic set up situations.

### gitwitit.ini

A list of rhyming aliases to teach git.
Save it to some place, or even include it right inside of your ```.gitconfig```

```
;; gitwitit.ini ;;
[alias]
  admit=merge
  aquit=blame
  befit=cherry-pick
  bit=grep
  chit=shortlog
  emit=push
  fit=rerere
  flit=stash
  it=checkout
  kit=config
  knit=rebase
  legit=pull
  mitt=fetch
  nit=prune
  omit=rm
  permit=add
  pit=bisect
  refit=clone
  remit=diff
  shit=revert
  sit=tag
  skit=log
  split=branch
  sprit=mv
  unfit=reset
  witit=status
  writ=reflog

```

### Include The File

To include it, the ```.gitconfig``` needs an include pointing to the path:

```
;;.gitconfig;;
...
[include]
  path=~/dotfiles/git/gitwitit.ini;
...
```


http://www.reddit.com/r/hiphopheads/comments/1lpv6a/i_am_big_boi_rapper_musician_actor_producer_ask/cc1llr0
