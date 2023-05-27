# task-recent_music_playlist


###########################################################################################################################################
$ This is a songs-user list repository out of which the played song gets added in the recent played list which can contain a limit of 3 songs
$ list of song-user pairs is stored, with each song linked to a user, user input for user name and song name where more than one user can have the same song
$ After this is done, a Recent Played List is created which has a fixed capacity say 'n', every played song by any user is added to the list initially being empty, when the capacity of  played songs in the list has reached then remove the very first song in the recent list and place the latest played song at last.
$ Recent played list is maintained as per the user who played which song and give a user based recent played songs as well.
###########################################################################################################################################


TEST----
###########################################################################################################################################
$$$ The above logic is tested in the following way using the TestNG framework:
$. Multiple song-user pairs are entered and mapped
$. recent played songs list are added in the recent played list and overall recent played songs and recent played songs as per user are generated and asserted.
