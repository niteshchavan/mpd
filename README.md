# mpd
MPD audio config

audio_output {
        type            "alsa"
        
        name            "ALSA"
        
        device          "default"
        
        format          "44100:32:2"
        
        mixer_type      "hardware"
        
        mixer_control   "Speaker"
        
        mixer_index     "0"

}
