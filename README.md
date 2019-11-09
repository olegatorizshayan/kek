# audio:
	- add %path
	Load audio file from %path
	
	- remove %id
	Remove loaded file by %id
	
	- info %id
	Get info for %id audio
	
	- list
	List all loaded audio files and their id's

# track:
	- add %name
	
	- remove %id
	
	- link %id %f_id
	Link %id track to %f_id fragment
	
	- unlink %id %f_id
	Unlink %id track from %f_id fragment
	
	- mute %id
	Inverts state of mute
	
	- solo %id
	
	- volume %id %value
	
	- gain %id %value
	
	- pan %id %value
	
	- info %id
	
	- list
	
# fragment:
	- add %a_id
	Create and link new fragment to the audio %a_id
	
	- remove %id
	Delete and unlink fragment from the audio %a_id
	
	- crop %id %crop_from %crop_to
	
	- offset %id %offset
	
	- info %id
	
	- list

# render:
	- session %path
	Create mix from all tracks in session and save it to %path

# session:
	- create %name %file_path %sample_rate
	Create session with %name and autosave it in %file_path. Supported %sample_rate now is 48kHz only.
	- link %id
	Link trek %id to created session

# codec 
	- init
	Search and load codec libs( if you have windows 32bit delete folders x64)

	- list
# quit
