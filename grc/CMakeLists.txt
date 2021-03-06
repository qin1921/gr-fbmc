# Copyright 2011 Free Software Foundation, Inc.
#
# This file is part of GNU Radio
#
# GNU Radio is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3, or (at your option)
# any later version.
#
# GNU Radio is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with GNU Radio; see the file COPYING.  If not, write to
# the Free Software Foundation, Inc., 51 Franklin Street,
# Boston, MA 02110-1301, USA.
install(FILES
    fbmc_configuration.xml
    fbmc_apply_betas_vcvc.xml
    fbmc_serial_to_parallel_cvc.xml
    fbmc_serialize_iq_vcvc.xml
    fbmc_polyphase_filterbank_vcvc.xml
    fbmc_output_commutator_vcc.xml
    fbmc_simple_frame_generator_vcvc.xml
    fbmc_input_commutator_cvc.xml
    fbmc_combine_iq_vcvc.xml
    fbmc_parallel_to_serial_vcc.xml
    fbmc_symbols_to_bits_cb.xml
    fbmc_preamble_insertion_vcvc.xml
    fbmc_frame_sync_cc.xml
    fbmc_coarse_cfo_correction.xml
    fbmc_rx_polyphase_cvc.xml
    fbmc_rx_polyphase_kernel.xml
    fbmc_rx_sdft_cvc.xml
    fbmc_rx_sdft_kernel.xml
    fbmc_tx_sdft_vcc.xml
    fbmc_tx_sdft_kernel.xml
    fbmc_rx_domain_cvc.xml
    fbmc_rx_domain_kernel.xml
    fbmc_frame_generator_bvc.xml
    fbmc_deframer_vcb.xml
    fbmc_multichannel_frame_generator_bvc.xml
    fbmc_multichannel_deframer_vcb.xml
    fbmc_multichannel_frame_sync_cc.xml
    fbmc_time_freq_sync_cc.xml
    fbmc_sync_configuration.xml
    fbmc_phase_sync_cc.xml
    fbmc_subchannel_frame_generator_bvc.xml
    fbmc_sliding_fft_cvc.xml
    fbmc_channel_estimator_vcvc.xml
    fbmc_channel_equalizer_vcvc.xml
    fbmc_subchannel_deframer_vcb.xml
    fbmc_tx_dummy_mixer_cc.xml
    fbmc_cazac_sync_cc.xml
    fbmc_correlator_postprocessor_cf.xml
    fbmc_frame_detector.xml DESTINATION share/gnuradio/grc/blocks
)
