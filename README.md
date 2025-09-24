**Git**
><H3>Changes in old commits will lead to change in hash of current commits</H3>
<p>
  Old: 7d76184 staged,
    1c31c73 tracked new txt,
    fb46707 initial commit
</p>

><h3>After Change of old commit</h3>
<h5>Here I changed the inital commit file a.txt using rebase edit</h5>
<P>
  New: 89d9872 staged,
    6208013 Rebased the tree,
    fb46707 initial commit
</P>
<h4>How commits are affected?</h4>

<p>1.When you open the interactive rebase (git rebase -i <base>), Git shows a list of commits to replay in order.

2.If you change pick → edit on any commit, Git will pause at that commit during the replay.

3.You can only edit the commit you marked edit. All later commits are unaffected until Git replays them.</p>
