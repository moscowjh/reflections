
## GitHub Reflection Chapter 2

#### What happens when you initialize a repository? Why do you need to do it?

.git metadata file is created.  Because it is a necessary precondition to `git add`

#### How is the staging area different from the working directory and the repository? What value do you think it offers?

It gives you a chance to make sure you have all the directories you need ready to commit and to run some final tests.

####How can you use the staging area to make sure you have one commit per logical change?

You can run `git diff` to make verify that you haven't added more changes.

#### What are some situations when branches would be helpful in keeping your history organized? How would branches help?

Trying out a new experimental featue when bug-fixing and other maintenance happening on Master.  A new language edition.

#### How do the diagrams help you visualize the branch structure?
Branches visualize the fact that changes/commits to specific branch are not in another branch (for instance, master).  This reminds you that the branches need to be merged in order to combine changes. Also provides a very good representation of what "unreachable" means.

#### What is the result of merging two branches together? Why do we represent it in the diagram the way we do?

Changes are combined in one file. Branches are brought back together and one is deleted.

#### What are the pros and cons of Git’s automatic merging vs. always doing merges manually?

Automatic is more algorithimic so less prone to human error. Manually is important in instances where a machine can't distinguish between kinds of changes to similar code.
